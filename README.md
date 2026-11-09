Import math
def calculate_Q(D):
	C = 50
	H = 30
	Q = math.sqrt((2*C*D)/H)
	return int(Q)

D = int(input("Enter D: "))
print(calculate_Q(D)
