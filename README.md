# application-week-3-p0-solved
**TO GET THIS SOLUTION VISIT:** [Application Week 3 P0 Solved](https://www.ankitcodinghub.com/product/application-p0-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124724&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Application Week 3  P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Application of Matlab for Finance

Week 3

I Input and Output, Reading from and Writing data

I Plot and SubPlothttps://.com I CW

Q1 Hints: datenum(.)

Add Input/Output

I xlsread(.)xlswrite(.)

I csvread(.)https://.comcsvwrite(.) I readtable(.)writetable(.) I save(.)load(.)

Add

xlsread(.)

I num = xlsread(filename) reads numeric data from the first

sheet of Excel file named filename, and store the data into a

matrix called num

I num = xlsread(filename, sheet) reads the specified worksheet I num = xlsread(filename, sheet, range) reads the specified worksheet and rangehttps://.com

I filename, sheet and range are strings enclosed in single quotes: data = xlsread(‘Stock.xls’,’Price’, ‘A1:B100’)

xlswrite(.)

I xlswrite(filename, M) writes matrix M to the first worksheet in the Excel file filename

I xlswrite(filename, M, sheet) writes matrix M to the specified worksheethttps://.comsheet in the Excel file filename

I xlswrite(filename, M, sheet, range) writes matrix M to a rectangular region specified by range

I filename, sheet and range are strings enclosed in single quotes I

Eg.Add xlswrite (‘MyOutput.xls’,Returns,’SP500′,’A1:A50′) Exercises 1

I Use the xlsread() function to read information from the excel file Stock.xls sheet Price into MATLAB with a matrix called data.

I Store the first column of data in a variable called stock_price_1 and the second column of data in a variable

calledhttps://.comstock_price_2

I Help function tick2ret(), and use it to calculate simple return of each stock, naming stock_return_1 and stock_return_2 respectively.

I Write the returns into a news excel file calledAdd Returns.xls with

two new sheets named returns_1 and returns_2 respectively. Exercises 1

1 data = xlsread(‘Stock.xls’, ‘Price’); 2

3 stock_price_1 = data(:,1);

4 stock_price_2 = data(:,2);https://.com 5

6 % calculate return

7 stock_return_1 = tick2ret(stock_price_1); 8 stock_return_2 = tick2ret(stock_price_2); 10 xlswrite(Add ‘Returns.xls’, stock_return_1, ‘return_1’); 9

11 xlswrite(‘Returns.xls’, stock_return_2, ‘return_2’);

csvread(.)

I M = csvread(filename) reads a comma-separated value formatted file from filename and stored the data in M.

I There is only one sheet in a .csv file

I The code requires the .csv file contains only numeric data

I M = csvread(filename, R1, C1)https://.comreads data from file starting the specific row R1 and column C1. The R1 and C1 arguments are zero based, so that R1=0 and C1=0 specify the first value in the file (Cell ’A1’).

I Hint: row (col) = actual file row (column) number -1

I M = csvread(filename, R1, C1, [R1 C1 R2 C2]);Add reads only the range specified.

I Eg. M = csvread(‘data.csv’,0,0,[0,0,6,1]) reads data in range of ’A1’ to ’B7’ from file data.csv

csvwrite(.)

I csvwrite(filename,M) writes matrix M into .csv file filename, which is a string enclosed in single quotes.

I csvwrite(filename, M,R1,C1) writes matrix M into the specified row R1 and column C1 offset. Note R1=0 and C1=0 specify the first value in the file.https://.com

I Note2: csvread() and csvwrit() only work with numeric values, and won’t

not work for csv files with a mix of text and numeric

values. Mac usersAdd

please use the readtable() with a ‘Format‘ parameter to specify

the data types for each columns.

readtable and writetable

I T = readtable(filename, ‘Format’, format_specs) create

a table T from column-oriented data such .csv, .txt or .dat.

I T = readtable(‘Price.xls’,’Format’, ‘%D%s%f%d’)

I All data from ‘Price.xls’ is stored in table variable T I ‘Format’ is the option name argument indicating the following

(3https://.comrd) input is the format specification I ‘%D%s%f%d’ is the specification value of ’Format’.

I ‘%’ stands a column indicator: 4’%’= 4 columns in our data file. I 1st column has datetime object (‘%D’)

Add I 2nd column is string (‘%s’),

I 3rd column is floating number (‘%f’)

I 4th column is integer format (‘%d’)

I writetable(your_table, filename) saves the Matlab table to an external data file.

save and load

I save(‘my_dataset.mat’, var1, var2, ..) saves selected

variables (var1, var2, …) in the current workspace to the matfile

named ‘my_dataset.mat’.

I load(https://.com’my_dataset.mat’, var1, var2, ..) loads variables (var1, var2, …) from datafile ‘my_dataset.mat’ into the current workspace.

I Observe the data format of file AAPL.csv, read the data using csvread() function into matrix aapl_csv

I Comment on why the code does not work, what you should do to fixhttps://.com the issue?

I still use csvread()

I use xlsread() to read both numeric data into aapl_num and Add

textual data into aapl_txt Exercises 2.a

1

aapl_csv = csvread(‘AAPL.csv’);

4 https://.com

5 % Read only numeric data from cell B2 6 % To refer cell in csvread, row=(B)2-1=1, col=2-1=1

7 aapl_csv = csvread(‘AAPL.csv’,1,1); 8

9 %Add Read with xlsread store num in aapl_xls and string in txt

10 [aapl_num, aapl_txt] = xlsread(‘AAPL.csv’);

Exercises 2.b

I Read AAPL.csv using readtable() function into table name aapl

I The format of data in AAPL.csv is Datetime, float, float, float, float, integer, float (specification is ‘%D%f%f%f%f%d%f’)

I Calculate simple return by using AAPL’s adjusted close price.

https://.comI Use the period (.) to refer sequences in a table: aapl.AdjClose

I Store the return into the aapl table under column name Return (Ensure the size of returns matches with length of the table)

I Save the updated table to a new .csv file namedAdd output_AAPL.csv.

I Save the table as AAPL.mat matfile. Clear the current workspace, and then load the dataset back to our workspace using load(). Exercises 2b

1 aapl = readtable(‘AAPL.csv’, ‘Format’, ‘%D%f%f%f%f%d%f’); 2 aapl_ret = tick2ret(aapl.AdjClose);

3

4 % match the return length with the table with the first … https://.comday return = 0

5 ret = [0; aapl_ret]; 6 aapl.Return = ret; 7 writetable(aapl, ‘output_AAPL.csv’); 8

9 %Add save and load

10 save(‘AAPL.mat’,’aapl’)

11 clear all 12 load(‘AAPL.mat’)

Summary

I xlsread can read csv file, but csvread cannot read excel file.

I When all data are numbers,https://.comcsvread is faster and preferred.

I When the data contain multiple formats such as dates, number and string, xlsread and readtable allow flexibility.

Add Simple Time Series Plot

https://.com

I Create a simple time-series plot of the adjusted close price of AAPL I Add relevant title, label and legend.

1 figure % create figure environment

3 legend(‘Adjusted Close Price’, ‘Location’,’NorthWest’)

4 ylabel(‘Price’) 5 xlabel(Add ‘Year’)

Simple Time Series Plot

https://.com Add

SubPlot

I Now create a figure with 2 sub-plot on AAPL

I The top panel plots the time-series of the adjusted close price I The lower panel is a area plot of the stock volume.

5

xlabel(https://.com’Year’)

;

6

9 legend(‘Stock Volume’, ‘Location’,’NorthEast’);

10 ylabel(Add

‘Volume’);

11 xlabel(‘Year’);

I subplot(m,n,p) create a figure with various plots I The actual plot codes of plotting comes after subplot(m,n,p)

I m,n define the plots layout structure: m rows n column panels.

I p defines which sub-plot is defined in the following codes.

SubPlot

https://.com Add

Hint: CW Q1-How to separate the data

it for the coding

I Option 2: with readtable(.)

%% Hints: CW Q1

% e.g., exercise 2.b 2 % if data = readtable(.) with %D for dates format

5 data_is = aapl(1:cut,:); % read in-sample

6 data_oos = aapl(cut+1:end,:); % read out-sample

Add

I aapl(1:cut,:) reads row 1 up to row cut as in-sample data; I aapl(cut+1:end,:) reads row cut+1 up to the end row as outofsample data.

Hint: CW Q1-How to separate the data

I Option 3: with xlsread(.), datenum(.) and datestr(.)

1 % if [data, txt] = xlsread(.). e.g., exercise 1

4 t_num = datenum(t_string, ‘dd/mm/yyyy’);

https://.com5 target_date = datenum(’18/01/2005′,’dd/mm/yyyy’) 6

cut = find(t_num == target_date); 7 data_is = aapl_num(1:cut,:); 8 data_oos = aapl_num(cut+1:end,:);

I Input &amp; Output: You can start with the coursework question 1

I Figures: plot, subplothttps://.com

Add
