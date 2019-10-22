# add-details-of-customer-using-dictionary


def add_cust(id,name,age,fav_movies):
    cus_dict['id'] = id
    cus_dict['name'] = name
    cus_dict['age'] = age
    cus_dict['fav_movies'] = fav_movies

    for key,value in cus_dict.items():
        print(f'{key} : {value}')



id = int(input('enter the customer id:  '))
name = input('enter the customer name:  ')
age = int(input('enter the customer age:  '))
fav_mov = input('enter the customer fav_movies with seperstted comma').split(',')

add_cust(id,name,age,fav_mov)
