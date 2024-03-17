# Max-integer-calculation
You're given two integers X and Y. Find the maximum integer you can get by applying any of the following three operations - a) X - Y b) X + Y c) X * Y Input You're given two integers - X and Y. ( -103 &lt;= X, Y &lt;= 103). Output Print the maximum integer.

def max_integer(X, Y):
    result1 = X - Y
    result2 = X + Y
    result3 = X * Y
    return max(result1, result2, result3)

X, Y = map(int, input().split())

print(max_integer(X, Y))
