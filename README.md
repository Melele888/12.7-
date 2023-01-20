# 12.7-
per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
money = 200000
deposit = []
for key in per_cent: deposit.append(per_cent[key] * money / 100)
max_deposit = max(deposit)
print(deposit)
print("Максимальная сумма, которую я могу заработать — " + str(max_deposit))

