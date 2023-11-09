import pandas as pd

d = {'Индикатор': [1, 2, 3, 4, 5,6], 'Бағасы': [170,130,150,160,155,189], 'Кіріс': [458,505,489,478,325,555]}

df = pd.DataFrame(data=d)

print(df)

count_column = df.shape[1]
print("Баған саны:")
print(count_column)
count_row = df.shape[0]
print("Жолдар саны:")
print(count_row)
