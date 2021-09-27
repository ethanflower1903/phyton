def letter_nums(digits):
        phone = [[],[], ['a', 'b', 'c'], ['d', 'e', 'f'], ['g', 'h', 'i'], ['j', 'k', 'l'], ['m', 'n', 'o'], ['p', 'q', 'r', 's'],
        ['t', 'u', 'v'], ['w', 'x', 'y', 'z']]
        if len(digits) == 0:
            return []
    
        new_list = phone[int(digits[0])]
        for i in range(1, len(digits)):
            temp_list = phone[int(digits[i])]
            updated_list = []
            for k in new_list:
                for j in temp_list:
                    updated_list.append(k+j)
            new_list = updated_list        
        return new_list
