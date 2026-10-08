[finalprojectmenu.py](https://github.com/user-attachments/files/33181960/finalprojectmenu.py)






print("welcome to rona land😋")
while True:
    phone = input("Please enter your phone number: ")
    if phone.isdigit() and len(phone) >= 10:
        break
    print("Invalid number. Use digits only (at least 10 digits).")


list_resid_koli=[]

while True :
    menu=input("1.resturant 2.fastfood 3.cafe 4.mexican food 5.exit:")
    if menu == "5":
         break
    match menu :
            case "1":
                resturant_menu=input("1.chicken kabab rice 2.kaba kobede rice 3.fesenjan 4.ghorme sabzi 5.zereshk polo 6.bagali polo 7.ghemey 8.sabzi polo mahi 9.adas polo 10.dizi 11.exit.")
                match resturant_menu:
                    case"1":
                        num_chickenkababrice=int(input("how many chicken kabab rice do you want:"))
                        price_chickenkabrice=num_chickenkababrice*600*1.1
                        list_resid_koli.append(price_chickenkabrice)
                    case"2":
                        num_kababkobederice=int(input("how many kabab kabab rice do you want:"))
                        price_kababkobederice=num_kababkobederice*750*1.1
                        list_resid_koli.append(price_kababkobederice)
                       
                    case"3":
                        num_fesenjan=int(input("how many fesenjan do you want:"))
                        price_fesenjan=num_fesenjan*650*1.1
                        list_resid_koli.append(price_fesenjan)
                    case"4":
                        num_ghorme_sabzi =int(input("how many ghorme sabzi  do you want:"))
                        price_ghorme_sabzi=num_ghorme_sabzi*675*1.1
                        list_resid_koli.append(price_ghorme_sabzi)    
                    case"5":
                        num_zereshk_polo=int(input("how many zereshk polo do you want:"))
                        price_zereshk_polo=num_zereshk_polo*640*1.1
                        list_resid_koli.append(price_zereshk_polo)

                    case"6":
                        num_bagali_polo=int(input("how many bagali polo do you want:"))
                        price_bagali_polo=num_bagali_polo*785*1.1
                        list_resid_koli.append(price_bagali_polo)

                    case"7":
                        num_ghemey=int(input("how many ghemey do you want:"))
                        price_ghemey=num_ghemey*645*1.1
                        list_resid_koli.append(price_ghemey)

                    case"8":
                        num_sabzi_polo_mahi=int(input("how many sabzi polo mahi do you want:"))
                        price_sabzi_polo_mahi=num_sabzi_polo_mahi*550*1.1
                        list_resid_koli.append(price_sabzi_polo_mahi)

                    case"9":
                        num_adas_polo=int(input("how many adas polo do you want:"))
                        price_adas_polo=num_adas_polo*340*1.1
                        list_resid_koli.append(price_adas_polo)

                    case"10":
                        num_dizi=int(input("how many dizi do you want:"))
                        price_dizi=num_dizi*800*1.1
                        list_resid_koli.append(price_dizi)

                    case"11":
                        print("mersi for coming! nooshe jan")
                        




            case "2" :
                fastfood_menu=input("1.Cheeseburger 2.Margherita Pizza 3.Veggie Bite 4.Chicken Wings 5.Chicken Sandwich 6.alferdo pasta 7.french fies 8.fried chicken 9.Chicken Nuggets 10.Spicy Chicken Wings 11.exit") 

                match fastfood_menu:
                    case "1":
                        num_Cheeseburger=int(input("how many Cheeseburger do you want:"))                       
                        price_cheeseburger=num_Cheeseburger*750*1.1
                        list_resid_koli.append(price_cheeseburger)
                         
                    case "2" :
                        num_Margherita_Pizza=int(input("how many Margherita Pizza do you want:"))                       
                        price_Margherita_Pizza=num_Margherita_Pizza*800*1.1
                        list_resid_koli.append(price_Margherita_Pizza)
                        
                    case "3" :
                        num_Veggie_Bite=int(input("how many veggie bite do you want:"))                                  
                        price_Veggie_Bite=num_Veggie_Bite*310*1.1
                        list_resid_koli.append(price_Veggie_Bite)
                    case "4" :
                        num_Chicken_Wings =int(input("how many Chicken Wings  do you want:"))                       
                        price_Chicken_Wings =num_Chicken_Wings*780*1.1
                        list_resid_koli.append(price_Chicken_Wings)
                    case"5" :
                        num_Chicken_sadnwich =int(input("how many Chicken sandwich  do you want:"))                       
                        price_Chicken_sandwich =num_Chicken_sadnwich*385*1.1
                        list_resid_koli.append(price_Chicken_sandwich)
                        
                    case"6" :
                        num_alferdo_pasta=int(input("how many alferdo pasta do you want:"))                       
                        price_alferdo_pasta=num_alferdo_pasta*875*1.1
                        list_resid_koli.append(price_alferdo_pasta) 
                    case"7" :
                        num_french_fies=int(input("how many french fies do you want:"))                       
                        price_french_fies=num_french_fies*250*1.1
                        list_resid_koli.append(price_french_fies) 
                    case"8" :
                        num_fried_chicken=int(input("how many fried chicken do you want:"))                       
                        price_fried_chicken=num_fried_chicken*785*1.1
                        list_resid_koli.append(price_fried_chicken)  
                    case"9" :
                        num_Chicken_Nuggets=int(input("how many Chicken Nuggets do you want:"))                       
                        price_Chicken_Nuggets=num_Chicken_Nuggets*438*1.1
                        list_resid_koli.append(price_Chicken_Nuggets)   
                    case"10" :
                        num_Spicy_Chicken_Wings=int(input("how many Spicy Chicken Wings do you want:"))                       
                        price_Spicy_Chicken_Wings=num_Spicy_Chicken_Wings*795*1.1
                        list_resid_koli.append(price_Spicy_Chicken_Wings) 
                    case"11" :
                        print("🍔 Enjoy your meal! 🍟")  
                                  
      
                break
            case "3":
                cafe_menu=input("1.Iced Coffee 2.Iced Latte 3.strawberry matcha 4.Fresh Lemonade 5.Espresso 6.Americano 7.Hot Chocolate 8.Tea 9.Strawberry Lemonade 10.Water 11.exit")
                match cafe_menu:
                    case "1":
                        num_Iced_Coffee=int(input("how many Iced Coffee do you want:"))                       
                        price_Iced_Coffee=num_Iced_Coffee*180*1.1
                        list_resid_koli.append(price_Iced_Coffee)
                    case "2":
                        num_Iced_Latte=int(input("how many Iced Latte do you want:"))                       
                        price_Iced_Latte=num_Iced_Latte*185*1.1
                        list_resid_koli.append(price_Iced_Latte)
                    case "3":
                        num_strawberry_matcha=int(input("how many strawberry matcha do you want:"))                       
                        price_strawberry_matcha=num_strawberry_matcha*200*1.1
                        list_resid_koli.append(price_strawberry_matcha)
                    case "4":
                        num_Fresh_Lemonade=int(input("how many Fresh Lemonade do you want:"))                       
                        price_Fresh_Lemonade=num_Fresh_Lemonade*150*1.1
                        list_resid_koli.append(price_Fresh_Lemonade)
                    case"5":
                        num_Espresso=int(input("how many Espresso do you want:"))                       
                        price_Espresso=num_Espresso*120*1.1
                        list_resid_koli.append(price_Espresso)
                    case"6":
                        num_Americano=int(input("how many Americano do you want:"))                       
                        price_Americano=num_Americano*160*1.1
                        list_resid_koli.append(price_Americano)
                    case"7":
                        num_Hot_Chocolate=int(input("how many Hot Chocolate do you want:"))                       
                        price_Hot_Chocolate=num_Hot_Chocolate*135*1.1
                        list_resid_koli.append(price_Hot_Chocolate) 
                    case"8":
                        num_Tea=int(input("how many Tea do you want:"))                       
                        price_Tea=num_Tea*80*1.1
                        list_resid_koli.append(price_Tea)
                    case"9":
                        num_Strawberry_Lemonade=int(input("how many Strawberry Lemonade do you want:"))                       
                        price_Strawberry_Lemonade=num_Strawberry_Lemonade*185*1.1
                        list_resid_koli.append(price_Strawberry_Lemonade)
                    case"10":
                        num_Water=int(input("how many Water do you want:"))                       
                        price_Water=num_Water*10*1.1
                        list_resid_koli.append(price_Water)   
                    case"11": 
                        print("Thank you for coming to our cafe☕🍰")
                        
                    
                break
            case "4":
                mexican_food_menu=input("1.Chicken Tacos 2.Beef Tacos 3.Veggie Tacos 4.Chicken Burrito 5.Beef Burrito 6.Veggie Burrito 7.Cheesy Burrito 8.Chicken Enchiladas 9.Mexican Rice Bowl 10.Mexican Bean Bowl 11.Mexican Vanilla Ice Cream 12.exit")
                match mexican_food_menu:
                
                        case "1":
                            num_Chicken_Tacos=int(input("how many Chicken Tacos do you want:"))                       
                            price_Chicken_Tacos=num_Chicken_Tacos*760*1.1
                            list_resid_koli.append(price_Chicken_Tacos)
                        case "2":
                            num_Beef_Tacos=int(input("how many Beef Tacos do you want:"))                       
                            price_Beef_Tacos=num_Beef_Tacos*860*1.1
                            list_resid_koli.append(price_Beef_Tacos)
                        case "3":
                            num_Veggie_Tacos=int(input("how many Veggie Tacos do you want:"))                       
                            price_Veggie_Tacos=num_Veggie_Tacos*660*1.1
                            list_resid_koli.append(price_Veggie_Tacos)
                        case "4":
                           num_Chicken_Burrito=int(input("how many Chicken Burrito do you want:"))                       
                           price_Chicken_Burrito=num_Chicken_Burrito*750*1.1
                           list_resid_koli.append(price_Chicken_Burrito) 
                        case"5":
                           num_Beef_Burrito=int(input("how many Beef Burrito do you want:"))                       
                           price_Beef_Burrito=num_Beef_Burrito*850*1.1
                           list_resid_koli.append(price_Beef_Burrito)
                        case"6":
                           num_Veggie_Burrito=int(input("how many Veggie Burrito do you want:"))                       
                           price_Veggie_Burrito=num_Veggie_Burrito*650*1.1
                           list_resid_koli.append(price_Veggie_Burrito)
                        case"7":
                           num_Cheesy_Burrito=int(input("how many Cheesy Burrito do you want:"))                       
                           price_Cheesy_Burrito=num_Cheesy_Burrito*700*1.1
                           list_resid_koli.append(price_Cheesy_Burrito) 
                        case"8":
                           num_Chicken_Enchiladas=int(input("how many Chicken Enchiladas do you want:"))                       
                           price_Chicken_Enchiladas=num_Chicken_Enchiladas*555*1.1
                           list_resid_koli.append(price_Chicken_Enchiladas) 
                        case"9":
                           num_Mexican_Rice_Bowl=int(input("how manyMexican Rice Bowl do you want:"))                       
                           price_Mexican_Rice_Bowl=num_Mexican_Rice_Bowl*789*1.1
                           list_resid_koli.append(price_Mexican_Rice_Bowl) 
                        case"10":
                           num_Mexican_Bean_Bowl =int(input("how many Mexican Bean Bowl  do you want:"))                       
                           price_Mexican_Bean_Bowl=num_Mexican_Bean_Bowl*800*1.1
                           list_resid_koli.append(price_Mexican_Bean_Bowl) 
                        case"11":
                           num_Mexican_Vanilla_Ice_Cream=int(input("how many Mexican Vanilla Ice Cream do you want:"))                       
                           price_Mexican_Vanilla_Ice_Cream=num_Mexican_Vanilla_Ice_Cream*80*1.1
                           list_resid_koli.append(price_Mexican_Vanilla_Ice_Cream) 
                        case"12":
                         print("🌮 ¡Buen provecho! 🌶️🥑")
                         
print("Your total is:", round(sum(list_resid_koli), 2))
               
                                    
                             
                        
                            
                
        

    
           
                    
                    
        

                
                
            
