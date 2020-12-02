# STOP IT
README file of the final project ADS

## TABLE OF CONTENT

* [STOP IT] (# Stop it)
   * [ABOUT THE PROJECT] (# About the project)
   * [CODE] (#Code)
   * [MOCKUP] (# Mockup)
   * [CONTIBUTING] (#Contributing)



### ABOUT THE PROJECT 

Unfortunately for us, we are living in an era with many problems, from a worldwide pandemic caused due to the COVID-19 virus to the increase of racism in the USA and overall everywhere. With these problems and many more we tend to forget others that may have the same importance as those mentioned before, and one of those is BULLYING.

Even though we may not hear about it much, bullying has been increasing at an enormous rate during the last years mainly due to the advances in technology and a lot of kids and children having phones earlier which is an incentive for bullying to start (cyber bullying). But there are many more types of bullying in the world, more concretely 6, and they are causing missery to young kids and in the worse casea suicide. That is exactly why we as a group have decided to take action into this matter and encourage everyone to do it with us.

The solution we have thought about was an application, an application for everyone, curious people, witnesses and victims. Our application has been created so that everyone can understand what bullying really is and how big of a deal it represents to society as well as providing help to those lost kids suffering bullying or witnesses who do not know how to take action.

#### CODE


            elif option == 3:
                print('\nYou will receive help on how to help the person who is suffering bullying')
                print('\nWhich type of bullying have you witnessed')
                print('\nChoose from the following options: \n1. Sexual Bullying'
                      ' \n2. Prejudicial Bullying \n3. Verbal Bullying \n4. Relational Bullying \n5. Physical Bullying'
                      '\n6. Cyberbullying ')
                type = int(input('\nPlease enter the option number: '))
                useroption.append(type)
                if type == 1:
                    print('This type of bullying can evolve into more serious problems for which we recommend '
                          'contacting superior authorities such as the police or trained professionals.')

                elif type == 2:
                    print('We recommend to take immediate action by telling your family the problem and contacting the '
                          'principal of the school you are attending to and have them deal with the problem trough'
                          'talks and intense methods.')

                elif type == 3:
                    print('Research has shown that verbal bullying and name-calling has serious consequences and '
                          'can leave deep emotional scars. For this reason we strongly recommend you to get '
                          'professional help form different psychologist and contact the school in order to stop'
                          'and take action to stop the bullies. ')

                elif type == 4:
                    print('This type of bullying usually goes unnoticed but it does not matter it is less'
                          'harmful, in order to stop this you have to tell your family and even try to talk to'
                          'the bullies to make them understand your situation.')

                elif type == 5:
                    print('Since this type of bullying is the most obvious one because of the visible scars it leaves,'
                          'people would have probably noticed it and in case they have not taken action you have to'
                          'do it, contact the police and have them move to your school and contact the bullies since'
                          'physical damage can be reported and criminalized in many ways.')

                elif type == 6:
                    print('Cyberbullies often say things that they do not have the courage to say face-to-face. '
                          'Technology makes them feel anonymous, insulated, and detached from the situation. They may '
                          'go under the radar since they do not act in person but it does not make them less '
                          'dangerous. This type of bullying has caused many suicides and it has to be reported to the'
                          'authorities as soon as possible to stop it.')
                else:
                    print('\nInvalid Input. You have entered a number outside the range')

            elif option == 4:
                victimInfo=[]
                print('\nWe are here to help you!')
                print('\nYou are not alone!')
                print('\nDo you wanna share more detailed information with us therefore we can help you? \n1.Yes \n2.No')
                help=int(input("Please enter the option number:"))
                useroption.append(help)
                if help==1:
                    print("We are happy to help you:) \nThen could you please tell us that which type of bullying have you suffered?")
                    print('\nChoose from the following options: \n1. Sexual Bullying'
                      ' \n2. Prejudicial Bullying \n3. Verbal Bullying \n4. Relational Bullying \n5. Physical Bullying'
                      '\n6. Cyberbullying ')
                    type = int(input('\nPlease enter the option number: '))
                    if type == 1:
                        print('This type of bullying can evolve into more serious problems for which we recommend '
                              'contacting superior authorities such as the police or trained professionals.')
                        help2=('If you want us to contact with superior authorities for you, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we will find the closest superior authorities for you:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the superior authorities:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,addr,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 2:
                        print('We recommend to take immediate action by telling your family the problem and contacting the '
                              'principal of the school you are attending to and have them deal with the problem trough'
                              'talks and intense methods.')
                        help2=('If you want us to contact with your family and principal of school, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            parentTele=input("Please enter your parents' telephone number:")
                            school=input("Please enter the name of your school:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to your family and school:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,parentTele,school,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 3:
                        print('Research has shown that verbal bullying and name-calling has serious consequences and '
                              'can leave deep emotional scars. For this reason we strongly recommend you to get '
                              'professional help form different psychologist and contact the school in order to stop'
                              'and take action to stop the bullies. ')
                        help2=('If you want us to contact with the psychologist and principal of school, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we can find the appropriate psychologist for you:")
                            school=input("Please enter the name of your school:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the school and psychologist:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,addr,school,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 4:
                        print('This type of bullying usually goes unnoticed but it does not matter it is less'
                              'harmful, in order to stop this you have to tell your family and even try to talk to'
                              'the bullies to make them understand your situation.')
                        help2=('If you want us to contact with your family and the bullies, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            buName=input("Please enter the bullies' name:")
                            buTele=input("Please enter the bullies' telephone number:")
                            parentTele=input("Please enter your parents' telephone number:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to your family:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,buName,buTele,parentTele,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 5:
                        print('Since this type of bullying is the most obvious one because of the visible scars it leaves,'
                              'people would have probably noticed it and in case they have not taken action you have to'
                              'do it, contact the police and have them move to your school and contact the bullies since'
                              'physical damage can be reported and criminalized in many ways.')
                        help2=('If you want us to contact with the police and the bullies, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2 == 0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2 == 1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we can find the police office for you:")
                            schoolAddr=input("Please enter the address of your school, therefore the police can move to your school as soon as possible")
                            buName=input("Please enter the bullies' name:")
                            buTele=input("Please enter the bullies' telephone number:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the police:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele,addr,schoolAddr,buName,buTele,situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')

                    elif type == 6:
                        print('Cyberbullies often say things that they do not have the courage to say face-to-face. '
                              'Technology makes them feel anonymous, insulated, and detached from the situation. They may '
                              'go under the radar since they do not act in person but it does not make them less '
                              'dangerous. This type of bullying has caused many suicides and it has to be reported to the'
                              'authorities as soon as possible to stop it.')
                        help2=('If you want us to contact with authorities, please type 1; Else, please type 0')
                        useroption.append(help2)
                        if help2==0:
                            print('Great! We are always on your side! Wish you all the best :)')
                        elif help2==1:
                            name=input("Please enter your name:")
                            tele=input("Please enter your telephone number:")
                            addr=input("Please enter your address, therefore we will find the appropriate authorities for you:")
                            situ=input("Please describe the bullying in details information therefore we can transfer the message to the authorities:")
                            print("\nThank you for your cooperation! We will contact you as soon as possible if there's any further progress")
                            victimInfo.append(name,tele, addr, situ)
                        else:
                            print('\nInvalid Input. You have entered a number outside the range')
                    else:
                        print('\nInvalid Input. You have entered a number outside the range')

                elif help==2:
                    print("It's okay~ But please notice that it's not your fault at all. To be honest, you don't deserve this."
                          "If you want any help in the future, feel free to come to us. We are always here for you 😉")
                else:
                    print('\nInvalid Input. You have entered a number outside the range')

        else:
            print('Invalid Input. You have entered a number outside the range')
    except ValueError:
        print('You have entered a non numeric character')


main()

##### MOCKUP

https://user-images.githubusercontent.com/74672340/100921367-c192b980-34dc-11eb-967c-994e4101e37b.png

###### CONTRIBUTING
Students of IE University
* Patricia Cano
* Greta Ynglada
* Mónica Azcue
* Javier Elena
* Ximeng Zheng
