# Solution Approach
I created a **MySQL DATABASE** to store the collection of books. Let me explain the SCHEMA of the table through a diagram.

After creating the database I filled some dummy data collected from the library's computer. They were in the form of excel sheets. The above attributes were the columns of the Excel Sheets. 

Once I was done with the backend, I started working on the frontend. 
Java is a purely object oriented language and it can help me to quickly generate the objects representing the real world entities like BOOKS,MAGAZINES,CDS. 
The core java is based on the command line and i was looking for a **Graphical Interface**.
That need was fulfilled by the **'JAVA SWING API'**.

**JAVA SWING API** is the basic API which lets us create a Window based Graphical Software very quickly.
There were another primitives as well, like JAVA FX, Flutter , AWT's etc but I chose JAVA SWING on account of the direct customization as the code for generating the UI was based on JAVA i.e. for creating a FRAME you write 
```
  JFrame frame = new JFrame();
  frame.setBounds(124,124,124,124);
  frame.setBackgroundColor(new Color(#222444));
```
According to the need of the application I was obliged to proivide a EASY TO USE ui which was easy to adopt by the librarian. 

So, the first screen after logging in the application displays the current borrowed or issued books, CDS and magazines in seperate tables.

**-------- This was because the librarian said "In order to manage library when i start the computer, i need a proper list of issued and borrowed books on a daily basis ".**

On the home screen there were different tabs to go to different use cases of the application 
Following were the most important use cases of the application::
```
1. Borrow a book.
2. Issue a book.
3. Borrow and issue a CD, magazine.
4. Check student's card validity.
5. Log in librarians securely.
6. Edit details of the stored books,magazines,CDS etc.
7. Show how many books of each category i.e.
    FICTION ,ADVENTURE,EDUCATION ARE AVAILABLE.
``` 
**----------------------These were the basic requirements of the librarian from such a system.**

When You are in any use case of the application,if you cancel the operation by closing the window the application redirects you the home screen.

**------------This was the additional feature that was added after the project was completed and was started being used in the library.**

During my analysis and testing i found that application was taking some time to start if the data was big, so I got away with this issue by a loading screen to display the progress of initialization.


