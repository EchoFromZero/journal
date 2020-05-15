# Week 5/13-5/19
1. 5h Adjust the program
    Question-1: when I open "tsv" with Excel, sometimes ISBN is changed into "9.7814E+12". Then it will authomatically be changed into approximation "9781000000000," which also causes error when I run the python file. "ValueError: invalid literal for int() with base 10: '9.7814E+12'"
    I found the question online: https://stackoverflow.com/questions/22647042/how-to-save-excel-columns-with-long-numbers-into-csv
    I tried the method of putting in "=9780998829036"; it works as long as I don't make any other changes in the file. If I directly edit the file, the problem occurs again. (Which was the reason why I favor the txt file at first.)

    It seems that the most doable method is:
    Excel is trying to "help" you by formatting the input values. To avoid this, **do not double-click the file to open it**. Instead, open the Data tab and in the Get External Data section, click on From Text. Tell to transform the column of ISBN as text, instead of number.

    If editing in the Excel (tsv file), one needs to save it as (txt, tab delimited) (then changes it into tsv file).
    Question-1 solved.

    Question-2:  how to store all the results in the for loop? If I get search for the two books by the same author. 
    Solution: Store the results in a list. Then run a for loop to iterate the elements in the list.
    Question-2 solved.

2. 3h Can print out all the receipts when one checks out and all the receipts are stored in the file. 

3. 1h Currently I want to work on a daily report. In a txt file, that presents the total number books sold; Grand Total gains. It also presents books sold by day (May 14, 15, 16, ...): number of books sold in total; total gain/income by day; Details of the book sold by day. I think it relates to the time. But I don't know how to do that. Especially, that is to say, for example, today's current total, etc. It seems to relate to a period of time. 
The form would be something like this:
Total number of books that are sold:
Grand Total: $

May 14, 2020
Number of books that are sold in total:
Total: $
Details of books sold:
Title of the book, daily sold number

May 15, 2020
Number of books that are sold in total:
Total: $
Details of books sold:
Title of the book, daily sold number

4. Update the about.md

# Week 5/6 - 5/12
1. 1.5h Testing how to convert csv to db, how to convert db into the dictionary format. trying to figure out a way to save the rows into a new data
2. 10h Back to basic Python, dictionary,  list. adjust and tune the program ...
# Week 4/29 - 5/5
1. 1h Fix isbn search ... Title search / Author serach not working ...
2. 2.5h Build up an "Taking Order" pop-up window.
3. 1.5h Stuck in how to build up "Total price" // extracting information from the list(?) database?

# Week 4/22-4/28
1. 1h pip install pandas; explore pandas; pandas is a very useful tool for csv. It has a nice display of the information. But the data analysis part is not what I needed here for my project.
2. 1h Study a bookstore inventory program I downloaded. It uses sqlite3 to manage the bookstore inventory
3. 2h learn sqlite3: https://docs.python.org/2/library/sqlite3.html I think sqlite3 will be my frame of the program. 
4. 4h programming with sqlite3, tkinter. Figure out the basics of an inventory system. Don't know if there's an easy to import the information from csv to db? not sure how to display the data in a better way, like the data from pandas, also including the title line. next time I'll design the sell windows...

# Week 4/7-4/14
1. 2h create final projects file (bookstore), list the details of about.md, create a tentative booklist (csv) for testing. But don't know why in the author's categories, there is a pair of quotation marks. Really excited about this project. 
2. 3.5h Set up a barcode scanner; figuring out how to incorporate csv into a dictionary, how to search under csv.DictReader, but not wroking... Can print out the full list. Still working on the search function.
3. 4h work on the loops for the essential features of the inventory. Not sure if csv is a good idea to save the data. Still trying to figure out a way to mark down the sale without making the syntax too convoluted. 
4. 1.5h Plan to use sqlite3 as my database and tkinter as my interface.  


# Week 5 (Week 3/4-3/10)
1. install Jekyll, read articles: “Why Use a Static Site Generator?”, “Creating a website with WordPress: The good and the bad”, “What is Bootstrap? – The History and the Hype,” “Brutalism: The ‘ugly’ web design trend taking over the internet”
2. Start to use Jekyll, learn more about web hosting, GitHub Pages …
Was trying to configure a subdomain, but couldn’t understand “Navigate to your DNS provider and create a CNAME record that points your subdomain to the default domain for your site. For example, if you want to use the subdomain www.example.com for your user site, create a CNAME record that points www.example.com to <user>.github.io. For more information about how to create the correct record, see your DNS provider's documentation. ”
3. Pull in the Index.html we did in-class. Push it to the new repository. Now the page can be found under the domain “echofromzero.github.io”.
4. Spend more time on HTML and CSS: HTML on W3Schools: Surprised to know these little details for accessibility! Such as “The lang Attribute,” “Alt Attribute” Go through basic HTML tutorial to The id Attribute. <button onclick="document.location = 'default.asp'">HTML Tutorial</button>  … How to make it a link to website? Not sure.
After I push the codes to GitHub, why does the website not change to its latest version? (It takes a few seconds to change.)


# Week 4 (Week 2/26-3/3)
1. 11:00-12:00 (1h) Make a small program to random group students into small groups!
	Got a basic model! Done! v1
2. 8:50-12:00 (3h)	In v1: I need to change manually the number of groups, the number of members. I want to make it change according to needs. Version 2 done. Can remove absent students. Do groups of students as you want. 
3. (1h) Adjusting the version 2; testing with another roster. 
4. Reading  (2h): Read *A Web for Everyone: Chapters 1 and 2 How People with Disabilities Use the Web: Tools and Techniques (W3C)*; *Dear Developer, The Web Isn't About You*; *Two Bit History: The World Wide Web and Its Inventor*


# Week 3
1. 0.5h Get journal/goals into shape, push them to Github
2. 2.5h Learn Python 3 the hard way: 
    Fix ex16.py drill 3
    Finish ex16-22
3. 0.5h Ex23 is relatively difficult to understand. Got stuck in this. 
    Skip from Ex23 to Ex 28
4. 2.5h Finish ex29-38  review and learn: if, elif, else, loops, lists
    Ex35, a little complicated. 
    Ex37 symbol review pp.162-165
    Ex38, not sure about the last two lines


# Week 2
1. 1h Review command line, explore Github, push/commits from Command line to Github, install Anaconda
2. 1h Push/Commits to Github, explore Python, stuck by “This Python interpreter is in a conda environment, but the environment has not been activated.” Stuck in this issue for a while. 
3. 1h detour from the last issue; download python 3.8.1 from the official website, Figure out the error: SyntaxError: Missing parentheses in call to 'print' (I was learning from Python 2 book, but using Python 3), The statement above does not work in Python 3. In Python 3 you need to add parentheses around the value to be printed
4. 1h Ex3, I got hens “30.0”, instead of 30. I got eggs 6.75, instead of 7. (same reason, I guess) in Python 3, 7.0/4.0, 7/4 seem to be the same; Ex 4, instead “We need to put about 3 in each car.” I got “We need to put about 3.0 in each car.”     floating point number. ; Difference between double-quotes and single-quotes? Solved in Ex7.
5. 1h Ex7: I have “Cheese Burger” in two separate lines. Nor sure how to use comma in my version. Solved by the Python 3 training book; Ex8, But I don’t have access to ex9 and beyond. 
6. 1h Explore GCDI, PUG (CUNY Academic Commons), find the Python 3 hard way book; Finish Ex10 but don’t remember all the escape sequences; finish ex11.	
7. 1h Ex12, not sure about “If you’re on Windows try python3.6 -m pydoc input instead.”
    p.74, how to run the script with parameters on the command line.
    Ex15: Not sure how to do this: “Start python3.6 to start the python3.6 shell, and use open from the prompt just like in this program. Notice how you can open files and run read on them from within python3.6?” 
8. 1h Ex16: This is what happened when I press ControlC:
    ?Traceback (most recent call last):
    File "ex16.py", line 9, in <module>
    input("?")
    KeyboardInterrupt

    Not sure how to do Drill 3: “There’s too much repetition in this file. Use strings, formats, and escapes to print out line1,
    line2, and line3 with just one target.write() command instead of six”

# Week 1 
1. 1.5h Review the syllabus; review the command line (Git Bash), VS code. Went through Command line tutorial. 
2. 4.5h Review command line. Go into more details about Grep command. Finish all the readings
