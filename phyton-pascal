def pascal(n):
    if n == 1 :
        return [[1]]
    pas_list = [[1]]
    k = 2
    while k < n+1:
        new_list = []
        for i in range(k):
            if i == 0:
                new_list.append(1)
            elif i == (k-1):
                new_list.append(1)
            else:
                new_list.append(pas_list[k-2][i-1]+pas_list[k-2][i])
        pas_list.append(new_list)
        k += 1
    return pas_list
