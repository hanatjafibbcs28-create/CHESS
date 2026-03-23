t =int(input("Enter the no.of.test cases:"))
for _ in range(t):
        x = int(input().strip())
        s = input().strip()
        c_points = (s.count('C') * 2) + s.count('D')
        n_points = (s.count('N') * 2) + s.count('D')
        if c_points > n_points:
            print(60 * x)
        elif n_points > c_points:
            print(40 * x)
        else:
            print(55 * x)

