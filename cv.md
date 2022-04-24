## **Chursina Maria**


***Contact information***

 **Phone** *+375296683400*
 
 **email:** *machutka63@gmail.com*
 
**Telegram:** *@matrriok*

*instagram:** *_manya__01__*

### ***Briefly About Myself***
my goal is to get a good job in a good company,
I don’t have my own work experience yet,
but there is not much in other areas.
At the moment I am studying at VSU and I want to learn and acquire new knowledge that will help me in the future in developing and remembering my business

I'm new to programming language, but I'm already learning c++, assembler and many others. version control systems and language framing are studied at the initial stages.
Now I am developing in various directions and I want to learn languages in which it will be possible to write many programs and games for children. and make money from it.


### ***Skills***
1. assembler
2. c++
3. access
4. excel
5. word
6. github
```
using namespace std;

int main(int argc, char* argv[])
{
	int h, m, x1, x2,a,b;
	if (argc == 3)
	{
		char* number = argv[1];
		switch (*number)
		{
		case 'A': { cout << "You choose the FIRST task\n";
			cout << "Enter first point1";
			cin >> x1;
			cout << "Enter second point2";
			cin >> x2;
			if (x1 = x2) {
				cout << "Enter different points\n";
				cerr << "Enter different points\n";
			}
			else {
				cout << "The first coordinate is " << x1 << "\n";
				cout << "The second coordinate is " << x2 << "\n";
				cout << "The length of the segment is" << fabs(x1 - x2) << "\n";
			}
		}break;
	
		case 'B': { cout << "You choose the SECOND task\n";
			cout << "Enter the side mediana";
			cin >> m;
			cout << "Enter hight";
			cin >> h;
			if ((h < 0) && (m<0)) {
				cout << "Wrong length\n";
				cerr << "Wrong length\n";
			}
			else {
				cout << "the height of the trapezoid is " << h << "\n";
				cout << "the mediana of the trapezoid is " << m << "\n";
				cout << "the area of the trapezoid is " << (m*h)/2 << "\n";
			}
		}break;

		case 'C': { cout << "You choose the third task\n";
			cout << "Enter the first side of the rectangle ";
			cin >> a;
			cout << "Enter the second side of the rectangle ";
			cin >> b;
			if ((a < 0) && (b<0)) {
				cout << "error\n";
				cerr << "error\n";
			}
			else {
				cout << "the first side of the rectangle is " << a << "\n";
				cout << "the second side of the rectangle is " << b << "\n";
				cout << "area of a rectangle" << a*b << "\n";
			}
		}break;


		default: {
			cout << "No tasks\n";
			cerr << "No tasks\n";
		}break;

	
		}
	}
	else {
		cout << "Enter parameter\n";
		cerr << "Enter parameter\n";
	}
	system("pause");
	return 0;
} 
```




