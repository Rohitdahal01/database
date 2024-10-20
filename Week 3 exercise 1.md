# Assignment 2
select name, type from airport where iso_country = "FI";
![1](https://github.com/user-attachments/assets/0a9a8c26-9d57-4639-af09-16a10d73e0c0)

# Assignment 3
select name from airport where iso_country = "FI" order by name;
![2](https://github.com/user-attachments/assets/8ae7e66e-c08b-498f-ab2a-9f362d3f075c)

# Assignment 4
select name, type from airport where iso_country = "FI" order by type, name;
![3](https://github.com/user-attachments/assets/209240e7-44b0-47d3-b844-e169e92c7647)


# Assignment 5 
select name from country where name like "F%";
![4](https://github.com/user-attachments/assets/c885d9a7-bec1-4c3f-8cf4-a8188e4be82d)

# Assignment 6
select name from country where name like "%F%";
![6](https://github.com/user-attachments/assets/ede930e2-8ef1-4dc2-a146-92420ed35ca6)

# Assignment 7
select location from game where screen_name = "Vesa";
![7](https://github.com/user-attachments/assets/5bc82689-52d8-408c-8ccb-440051e8c362)

# Assignment 10
select screen_name, co2_budget, co2_consumed, @co2_left :=(co2_budget - co2_consumed) as co2_left from game where screen_name = "Ilkka";
![7](https://github.com/user-attachments/assets/641fc19e-b736-4f63-b718-ecd67dde2dd2)
