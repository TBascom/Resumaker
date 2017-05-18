Synopsis

Resumaker creates a resume by asking a user questions and formatting the answers into a printable text document.

Code Example

//Start asking questions and storing answers in document
		cout << "This part of the program will ask you basic questions found on a resume,\nthen store the answers in a text file called Resume.txt." << endl;
		//Basics
		cout << nameq;
		getline(cin, name);
		outFile << nameq << name << endl;
		cout << addressq;
		getline(cin, address);
		outFile << addressq << address << endl;
		cout << phonenumberq;
		getline(cin, phonenumber);
		outFile << phonenumberq << phonenumber << endl;
		cout << emailq;
		getline(cin, email);
		outFile << emailq << email << endl << endl << endl;

Motivation

This was done for the Q4 Computer Programming Final Project.

Installation

Ask us for an installation

Tests

Contributors

Send us money at a soon-to-be-set-up patreon account.
