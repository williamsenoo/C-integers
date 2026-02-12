#include <iostream>
#include <string>
using namespace std;

int main(){


// input two integers and return their sum 
int add(int a, int b){
	return a+b;
}



// input a string and return the number of vowels
int countVowels(const string& str){
	int count= 0;
	for(char c : str){
		switch(tolower(c)){
			case 'a':
			case 'e':
			case 'i':
			case 'o':
			case 'u':
			
			 count++;
		}
	}
	return count;
	}
	
	
	//input a list of integer and return their average
	double average(const vector<int>& numbers){
		if(numbers.empty()){
			throw runtime_error("cannot calculate average of an empty list");
		}
		int sum =0;
		for(int num : numbers){
			sum += num;
		}
		return static_cast<double>(sum) / numbers,size();
	}
	
	
	//input sentence and return the sentence with all vowels remove
	string removeVowels(cont string& sentence){
		string result;
		for (char c : sentence){
		}
		switch (tolower (c)){
			    case'a':
				case 'e':
					case 'i':
						case 'o':
							case 'u'
							
		break;
		default:
			result += c;
		
		}
	}
	return result;
	}
	
	
	
	
	//input list of strins and return longest string
	string longestString(const vector<string>& strings){
		if(strings.empty()){
			throw runtime_error("cannot find longeststring in an empty list");
		}
		string lowest = strings[0];
		for(const string& str : strings){
			if(str.length()> longest()){
				longest =str;
			}
		}
		return longest;
	}
	
	
	
	//input list of integers and return medain value
	double median (const vetor<int>& numbers){
		if (numbers.empty()){
			throw runtime_error("cannot calculate medain of an empty list");
		}
		vector<int> sortedNumbers = numbers;
		sort(sortedNumbers.begin(), sortedNumbers .end());
		size_t size = sortedNumbers.size();
		if (size % 2 == 0){
			return (sortedNumbers[size / 2 - 1] + sortedNumbers[size / 2]) / 2.0; 
		} else {
			return sortedNumbers[size / 2];
			
		}
	}
	
	
	//input list of integers and return new list with all even numbers removed 
	vector<removeEvens(const vector<int>& numbers){
		vector<int> results;
		for (num : numbers){
			if (num % 2 !=0){
				result.push_back(num);
			}
		}
		return result;
	}
	
	
	
	//input list of strings and return new list with string sorted in alphabetical order
	vector<string> sortstrings(const vector<string>& strings){
		vector<string> sortedStrings = strings;
		sort(sortedStrings.begin(),sortedStrings.end());
		return sortedStrings; 
	}
	
	
	
	//iput list of integers and return the sum of all integers
	int sum(const vector<int>& numbers){
		int sum = 0;
		for(int num : numbers){
			sum += num;
		}
		return sum;
	}
	
	
	
	
	//input list of string and return new list with all string string reversed 
	vector<string> reverseStrings(const vector <string>& strings){
		vector<string> reversedStrings;
		for(const string& str : strings){
			string reversedStr = str;
			reverse(reversedStr.begin(), reversedStr.end());
			reversedStrings.push_back(reversedStr);
		}
		return reversedStrings;
	
	}
	   }
