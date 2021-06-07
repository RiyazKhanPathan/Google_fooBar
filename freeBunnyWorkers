def solution(num_buns, num_required):
    from itertools import combinations
    keys,duplicateKeys = [[] for num in range(num_buns)],num_buns - num_required + 1
    list(map(lambda x: list(map(lambda y: keys[y].append(x[0]),x[1])),enumerate(combinations(range(num_buns),duplicateKeys))))
    return keys
