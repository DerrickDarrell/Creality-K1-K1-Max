## BOM

- 3x - 16T 5mm Bore timing gears (10mm belt - tall)
- 2x - 136mm closed loop belts (front)
- 1x - 132mm closed loop belt (rear)
- 1x - 20t 6mm bore timing gear (optional - for rear lead screw)
- 3x - nema 17 stepper motors (40Ncm or better)
- M3 screws of various lengths


## IMPORTANT

1. You're doing this willingly
2. I am not responsible if you damage your printer or whatever worse may come of it
3. This requires you drilling through the bottom panel
4. This will not work with the factory board
5. Custom z joints are not necessary. The factory ones have enough flex to allow z tilt
6. If you use the stepperonline motors listed bellow, you might need to swap the middle pins
7. Use blue loctite on all timing gear grub screws
8. K1 Max users will need to upgrade their power supply
9. If you don't know what you're doing and are asking a thousand questions, maybe you shouldn't be doing this


## HARDWARE USED

Stepper Motors
https://www.amazon.com/dp/B0B38GHRH8?ref=ppx_yo2ov_dt_b_product_details&th=1

Stepper Motors recommended
https://www.amazon.com/dp/B07LCK19D5?ref_=cm_sw_r_cso_cp_apin_dp_DVZ9QP0Z23W8TE2J9YJ6&starsLeft=1&skipTwisterOG=1

16T 5mm bore timing gears
https://www.amazon.com/dp/B07BT6DPX7?ref=ppx_yo2ov_dt_b_product_details&th=1

132mm closed loop belt
https://www.amazon.com/dp/B0CDP99VZB?ref=ppx_yo2ov_dt_b_product_details&th=1

136mm closed loop belts
https://www.amazon.com/dp/B07B5X74TX?psc=1&ref=ppx_yo2ov_dt_b_product_details

20T 6mm bore timing gear (optional)
https://www.amazon.com/dp/B07PPGQV6K?ref=ppx_yo2ov_dt_b_product_details&th=1

Drill bits
https://www.amazon.com/gp/product/B0C2TTG1SW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1

2.54mm JST-XH connectors (for stepperonline motors)
https://www.amazon.com/gp/product/B01MCZE2HM/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1


## OTHER INFO

The 20T timing gears on the front lead screws need to be flipped around. This allows you to sit the gear and belt lower on the motor's shaft for better stability. 

You will need to setup Z-Tilt in klipper, check the link below

https://www.klipper3d.org/Config_Reference.html?h=pixel#z_tilt

rotation_distance: 8
gear_ratio: 20:16


![2024-09-11_8f9d08bcb95b9](https://github.com/user-attachments/assets/6ddf3d51-2e46-4c4b-9ebd-a2e615cbe783)
![20240216_175003](https://github.com/user-attachments/assets/d5e1bd61-5321-46d9-be9b-8bc0aee126e7)
![20240216_194147](https://github.com/user-attachments/assets/b8507894-3ab1-4ec8-9788-71adb0fd563a)
![20240216_201554](https://github.com/user-attachments/assets/2a8f7eb8-f694-4a2c-9df1-74fd66d04bca)
![20240217_151309](https://github.com/user-attachments/assets/c2dc584b-1670-430d-b957-4e63e3679b52)
![20240217_151255](https://github.com/user-attachments/assets/ec61f45c-95f7-4cb8-a462-5db1311f93f3)







