# 1
select * from goal;
![1](https://github.com/user-attachments/assets/cafbcfed-e886-4ddd-9b80-92bade84c119)

# 2
select name, type from airport where iso_country = "FI";
![2](https://github.com/user-attachments/assets/c210c858-17bb-44a0-8c8e-955df9ca27ae)

# 3
select name from airport where iso_country = "FI" order by name;
![3](https://github.com/user-attachments/assets/9f5248f6-116f-4686-833c-ea7922606ed1)

# 4 
select name, type from airport where iso_country = "FI" order by type name;
![4](https://github.com/user-attachments/assets/f3ba2616-ec90-4844-9ce9-75b4b951ffca)

# 5
select name from country where name like "F&";
![5](https://github.com/user-attachments/assets/9ee0936c-132b-4baa-9ec2-7ec80b402502)

# 6 
select name from country where name like "%F%";
![6](https://github.com/user-attachments/assets/8ef65f25-27a0-4d67-a202-36d5ef5787dc)

# 7
[7](https://github.com/user-attachments/assets/8d6ce4e5-487f-46a2-ab77-f62c060477a5)
  select location from game where screen_name = "Vesa";

# 8
select co2_consumed from game where screen_name = "Ilkka";
![8](https://github.com/user-attachments/assets/47b28c71-0cd4-4346-bf65-bb8f53473b56)

# 9
select co2_budget from game limit 1;
![9](https://github.com/user-attachments/assets/66f0ddfc-145e-4388-9505-47a2381ee2cf)

# 10
select screen_name, co2_budget, co2_consumed, @co2_left :=(co2_budget - co2_consumed) as co2_left from game where screen_name = "Ilkka";
![10](https://github.com/user-attachments/assets/20d5693a-cdc9-4496-ab63-71eceb91d10d)

