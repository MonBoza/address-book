Describes: Contact();

Test: Its will create a constructor for all the contacts.
Code:Contact(firstName, lastName, phoneNumber);
Expected Out: Contact {firstName: "Ada", lastName: "Lovelace", phoneNumber: "503-555-1111"}

Test: It will create a method that joins firstName and lastName.
Code: Contact.fullName
Expected Output: "Ada Lovelace"

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