# COBOL

Cobol is a rather ancient language designed for business proposes. It has some interesting design properties that I like:

* It supports decimal numbers instead of binary ones as a primitive. That's very useful in a financial context (or some business ones), but not especially useful to almost all programmers, meaning that modern languages don't typically support it. This has made COBOL effectively impossible to replace.
* With COBOL being difficult to replace, you'd expect there to be lots of programmers keeping the COBOL systems we rely on afloat. But there are _none_. We have to bring old programmers out of retirement to keep these systems going because no modern programmers speak the language.
  * How this isn't considered a looming crisis I have no idea.
*   Maybe you could learn COBOL! Not for the cash, but because its design betrays a philosophy that I think all programmers should at least be exposed to, even if we don't want to _use_ it in our own code.

    * It's useful for reading other peoples', for example, or writing code that communicates what it's doing very clearly.
    * What I have in mind is its separation of its code into sections. There are four areas of a COBOL program, which it calls "divisions":
      *
        1. The Identification Division
        2. The Environment Division
        3. The Data Division
        4. The Procedure Division
    * Not all of these are mandatory inclusions in a COBOL program, but its imposed structure is nice. "Identification", for example, isn't just about the program: it's where the program's author is identified. "Environment" doesn't refer to a docker container: it's physical hardware the program expects to be run on. And so on.



## Links

* [Cobol's "Divisions" explained](https://www.microfocus.com/documentation/object-cobol/oc41books/lrcpro.htm)
* [The code that controls your money — a superb article on cobol from wealthsimple](https://www.wealthsimple.com/en-ca/magazine/cobol-controls-your-money)
