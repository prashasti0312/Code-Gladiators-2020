#include<stdio.h>
#include<algorithm>
#include<vector>
#include<iostream>

int main(int argc, char *a[])
{
    //Write code here
	int num_ingredients;

	std::vector<int> ingredients_required;
	std::vector<int> ingredients_quantity;

	std::cin>>num_ingredients;

	for(int i=0;i<num_ingredients;i++){
		int input_string;
		std::cin>>input_string;

		ingredients_required.push_back(input_string);
	}

	for(int i=0;i<num_ingredients;i++){
		int input_string;
		std::cin>>input_string;

		ingredients_quantity.push_back(input_string);
	}

	int minimum_number;

	for(int i=0;i<num_ingredients;i++){
		int quantity;

		quantity=ingredients_quantity[i]/ingredients_required[i];

		// initialise
		if(minimum_number==0){
			minimum_number=quantity;
		}
		else if(quantity<minimum_number){
			minimum_number=quantity;
		}
	}

	std::cout<<minimum_number<<"\n";

}
