Describes: Contact();

Test: Its will create a constructor for all the contacts.
Code:Contact(firstName, lastName, phoneNumber);
Expected Out: Contact {firstName: "Ada", lastName: "Lovelace", phoneNumber: "503-555-1111"}

Test: It will create a method that joins firstName and lastName.
Code: Contact.fullName
Expected Output: "Ada Lovelace"

Test: It will create a method that assigns ID's to contacts
Code: let addressBook = new AddressBook();
addressBook.addContact(new Contact("Ada", "Lovelace", "503-555-0100", "123@email.com));
let contactId = addressBook.assignId();
Expected Output: contacts: {
    1: {firstName: "Ada", lastName: "Lovelace", phoneNumber: "000-000-0000", emailAddress: 123@email.com, id: 1}
}

Test: It will create an object in Contacts() for addresses.
Code: Contact(homeAddress)
this.homeAddress = homeAddress 
Expected Output: 1: {firstName: "Ada", lastName: "Lovelace", phoneNumber: "000-000-0000", emailAddress: 123@email.com, id: 1, homeAddress: 1234 Address city,State 11111}

Test: It will create an object in Contacts() for addresses
Code: Contact (homeAddress)
this.homeAddress = homeAddress
Expected Output: 1 : {firstName: "Ada", lastName: "Lovelace", phoneNumber: "000-000-0000", emailAddress: 123@email.com, id: 1, homeAddress: 1234 Address city,State 11111}



Describes AddressBook();

Test: It will create and empty Object to store Contacts(); .
Code: function AddressBook() { this.contacts = {}; }
Expected Output: AddressBook; 
            contacts[]

Test: It will create a method that adds contacts to AddressBook().
Code: addressBook.addContact(contact);
AddressBook.addContact();
Expected Output: AddressBook;
                AddressBook {contacts: {…}}

Test: It will start current Id at 0
Code: this.currentId = 0;
Expected Output: AddressBook; [0]

Test: It will create a method thats assigns Ids to contacts.
Code: let contact = new Contact("Ada", "Lovelace", "503-555-0100");
AddressBook.assignId();
Expected Output: AddressBook; [2]

Test: It will create a method that finds the contact by Id.
Code: AddressBook.findContact();
if (this.contacts[id] !== undefined){
    return this.contacts[id];
}
return false;
Expected Output:contact.id;
               >1 
