# Design-Patterns-in-Java-The-Proxy-Pattern-Demonstration
Design Pattern Project in Java : The Proxy Pattern Demonstration

Project Proposal
I intend to design a Proxy Pattern that will allow a Client, by the use of the ATM Interface, to fetch the user’s bank account details from the Bank Class & perform basic operations on their account upon authentication via the use of a protection proxy.
The proxy will be implemented to allow the Client to request only certain operations from the bank class, via the ATM Interface, upon the User’s login credentials being authenticated by the Proxy.  Hence demonstrating the Proxy Patterns ability to provide an additional security layer, restricted access to the functionality of the Bank Object via the use of the Interface (the Subject) and the “lazy instantiation” of the Bank Object (the Real Object) via the Proxy.
My goal is to add the protection proxy object as a layer between the ATM Interface code and the Bank Class logic.
The Bank Object will contain an Array of Bank Account Details and some simple operation (getter and setter) methods.  Limited access to these operations will be restricted by the ATM Interface to allow the User to withdraw/desposit funds from his/her bank account & check current balance of the account via the Proxy.
Ultimately, The Proxy layer implemented in this program will provide a surrogate or placeholder for the Bank object, also known as the Real Subject, which in turn will provide the ability to control access to the Bank object.

