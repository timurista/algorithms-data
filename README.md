## Notes section

C++ uses a variety of types to declare itself.
One interesting thing about this language is that it uses std::cout, to mean from the std package include the out function. It also indicates the piping structure using the >> to mean out, and << to mean chain in. Also, unsigned variables can be used to indicate variables. `unsigned a = 2`. You can also use float which is 4 bytes or space for 38 zeroes and double which allows for double that amount (8 bytes). Basically the same


### Namespace
virtually everything is located in the namespace // global namespace like js?


## The C vocabulary
- declaration // name and type of something int time

## constructors
class C {
    public:
        explicit C(int x); // not default constructor
}

explicit prevents implicit type conversions...
this is using casting
explicit are prefered because they can prevent compilers from doing unexpected type conversion. Strings --> ints, etc.

## copy construcotr
class Widget
    public:
        Wget(); // default
        Wget(const Wget& rhs) // copy constructor
        Wget& operator=(const Wget& rhs) // copy assignment operator

Wget w2(w1);
// invoke copy assignment
w1 = w2


## undefined behavior
in C++ you can have undefined behavior

## parts of c++
template c++, TMP. C pass by value rule applies
Prefer consts, enums and inlines to #defines

