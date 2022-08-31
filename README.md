
#Begginer's code-Cheers


fst_name = input('Please enter your first name: ').strip().title()
the_name = fst_name.replace(' ','').replace('-','')
if fst_name == '':
    print('You did not enter any characters.')

elif not the_name.isalpha():
    print('Non alphabetic characters were entered.')

len_name = len(fst_name)
if len_name == 1 :
    print(f'{len_name} {fst_name}')
    print(f'There is {len_name} letter in {fst_name}.')
elif the_name.isalpha():
    the_name = len(the_name)
    for chr_counter, each_chr in enumerate(fst_name, start=1):
        print(f'{chr_counter} {each_chr}')
    print(f'There are {the_name} letters in {fst_name}.')






START_NUM = 1
# 'Please enter a message: '
enter_msg = input('Please enter a message: ').strip()
len_ms = len(enter_msg)
if enter_msg == '':
    print('You did not enter a message.')
else:
    
        
    for count_chr, each_chr in enumerate(enter_msg, start=1):
        if each_chr.isdigit():
            chr_type = 'digit'
        elif each_chr.isalpha():
            if each_chr.islower():
                chr_type = 'lower alpha'
            else:
                chr_type = 'upper alpha'
        elif each_chr.isspace():
            chr_type = 'space'
        else:
            chr_type = 'symbol'
        print(f'{count_chr:<2} {each_chr} - {chr_type}')




























dic={'a':12,'b':34,'jon':'boy','lili':'girl'}
list=[1,2,3,4]
tup=(1,2,3,4)
()#空元组
()
55,#—个值的元组
(55,)

s = {(1, 2, 3): "hello world"}
print(s[(1, 2, 3)], s[1, 2, 3])
访问字典里的值

把相应的键放入熟悉的方括弧，如下实例:

dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'};
 
print "dict['Name']: ", dict['Name'];
print "dict['Age']: ", dict['Age'];
#以上实例输出结果：
#dict['Name']: Zara
#dict['Age']: 7
三、修改字典

向字典添加新内容的方法是增加新的键/值对，修改或删除已有键/值
