# JustClickIt
An application to solve problem of people made by using C++

#include<iostream>
#include<conio.h>
#include<windows.h>
using namespace std;
class app
{
	
	public:
		char problem[50];
		int digit;
		int option;
		void putdata(void)
		{
			cout<<"Welcome To JustClickIt";
		    cout<<"\nOne Soluton for every problem";
			
		}
		void getdata(void)
		{
			
		    cout<<"\n 1. Air Tickets"<<"\n 2. Automobile"<<"\n 3. Apply for Loans"<<"\n 4. Bus"<<"\n 5. Book Hotels"<<"\n 6. Bills and Recharge"<<"\n 7. Banquets"<<"\n 8. Car Rentals";
			cout<<"\n Choose your problem :";
			cin>>digit;
				switch(digit)
			{
			case 1:
			{
				cout<<"You can book flight tickets from here";
				cout<<"\n From : ";
				cin>>problem;
				cout<<"\n To : ";
				cin>>problem;
				cout<<"\n Depart on : ";
				cin>>digit;
				cout<<"\n Number of Adults : ";
				cin>>digit;
				cout<<"\n Number of Children : ";
				cin>>digit;
				cout<<"\n Available Flights are : ";	
			}break;
			case 2:
			{
				cout<<"\n 1. Car 2. Bike ";
				cout<<"\n Choose between Car and Bike : ";
				cin>>option;
				if(option = 1)
				{
					cout<<"Choose the problem in your car : ";
				}
				else
				{
					cout<<"Choose the problem in your Bike : ";
				}
			}break;
			case 3:
				{
					cout<<"\n 1. Home Loan"<<"\n 2. Car Loan"<<"\n 3. Education Loan"<<"\n 4. Bussiness Loan"<<"\n 5. Credit Card Loan";
					cout<<"Choose the type of Loan, you want to take : ";
					cin>>option;
					
				}break;
				case 4:
					{
						cout<<"\nYou can book bus tickets from here";
					cout<<"\nFrom : ";
				cin>>problem;
				cout<<"\nTo : ";
				cin>>problem;
				cout<<"\nDepart on : ";
				cin>>digit;
				cout<<"\nNumber of Adults : ";
				cin>>digit;
				cout<<"\nNumber of Children : ";
				cin>>digit;
						cout<<"\nAvailable Buses are : ";
					}break;
					case 5:
						{
							cout<<"\nBook Hotels";
							cout<<"\nCity : ";
							cin>>option;
							cout<<"\nDate : ";
							cin>>digit;
							cout<<"\nAvailable Hotels are : ";
							
						}break;
						case 6:
							{
								cout<<"\nBills and Recharge";
								cout<<"\nEnter your Mobile Number : ";
								cin>>digit;
								cout<<"\nEnter the Amount : ";
								cin>>digit;
								cout<<"\nSelect your Network ";
								cout<<"\n 1. BSNL"<<"\n 2. Airtel"<<"\n 3. Idea"<<"\n 3. Jio"<<"\n 4. TATA DOCOMO"<<"\n 4. Vodafone\n";
							    cin>>digit;
							    cout<<"Enter your Email : ";
							    cin>>digit;
							}break;
							case 7:
							{
								cout<<"\n 1. All Banquet Halls"<<"\n 2. 5 Star Banquet Halls"<<"\n 3. AC Banquet Halls"<<"\n 4. Lawn For Events"<<"\n 5. Non AC Banquet Halls";
								cout<<"\n Choose your Hall : ";
								cin>>digit;
							}
							case 8:
								
					
		}
			
		}
};
int main()
{
	int i;
	app display;
	display.putdata();
	display.getdata();

}
