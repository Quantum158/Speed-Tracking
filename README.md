# Speed Tracking

[![Download](https://img.shields.io/github/v/release/Quantum158/Speed-Tracking)](https://github.com/Quantum158/Speed-Tracking/releases)
[![License](https://img.shields.io/github/license/Quantum158/Speed-Tracking)](./LICENSE)

An Excel spreadsheet template designed to assist coaches in tracking and analyzing several athlete's performance simutaniously.
Provided without the use of VBA with the standard .xlsx file extension

* [Getting Started](#getting-started)
    * [Adding a New Athlete](#adding-a-new-athlete)
    * [Adding Data to an Athletes Page](#adding-data-to-an-athletes-page)
      * [Add an Age Category to an Athlete Page](#adding-an-age-category-to-an-athlete)
    * [Renaming Athlete Pages](#renaming-athlete-pages)
    * [Organizing the Index Sheet](#organizing-the-order-of-names-on-the-index-sheet)
    * [Expanding Table Lengths](#expanding-table-lengths)
* [Usage with Other Spreadsheet Software](#usage-with-other-spreadsheet-software)
* [Known Bugs](#known-bugs)
* [License](#license)
* [Contact](#contact)


# Getting Started
First, [download the repository](https://github.com/Quantum158/Speed-Tracking/archive/v1.0.1.zip "Direct Download"). It will contain: This README file, the License, and the Excel file.
The first time you open the Excel sheet, you will see 2 tabs:
    Index, and (BLANK).
* "Index" will contain a list of key information from all the athletes personal pages
* "(BLANK)" is a template sheet used to add new athletes


## Adding a New Athlete
(Accurate for Windows 10)
First, Duplicate the "(BLANK)" sheet.

* Right click on the tab, Click "Move or Copy", Select a position for the sheet to appear, click "Make a copy" at the bottom of the popup, then press "OK".

Then, move the tab you created so it is positioned in-between Index and (BLANK) (if it is not already).


### Renaming Athlete Pages
To rename an athletes page, right click on the tab you wish to edit and click "Rename". When finished, you will see the new name update in side of the spreadsheet.

**Note: You are not able to edit the name of an athlete any other way, attempting to edit the cell containing the name will not work**


### Adding Data to an Athletes Page
Athlete pages can support a few different pieces of data:
    * Date
    * Day Notes
    * Times
    * Coaching & Training Priorities
Simply type your data into the respective column. Analysis columns will automatically populate when this data is provided
Coaching and training priority columns can be found to the right of the time grid.


#### Adding an Age Category to an Athlete
To the right of the athletes name on their spreadsheet is the cell labelled "Category". 
Click on this cell, then select the small triangle to the right to open the category drop-down menu.


### Organizing the Order of Names on the "Index" Sheet
The index sheet grabs the order from the physical order of the tabs located between the "Index" and "(BLANK)" sheets.
To change the order, simply rearrange the tabs by dragging and dropping them to a new position in the tab list (ensuring they are still positioned between "Index" and "(BLANK)", otherwise they will not be detected).

**Note: Do not use Excel's built-in sort functionality, it will break the page**

### Expanding Table Lengths
(These steps will work for both Athlete pages as well as the Index Page)
In the event that the length of the chart is not enough, it can be expanded with a few steps

   1) **Unprotect the Tab**: Go to "Review" in the top bar, then click "Unprotect Sheet". The password is "Unlock"
   2) **Unhide Additional Rows**: Select all cells of the tab by clicking the diagonal triangle in the top left of the window (where the letters and numbers meet)
   3) Right Click on any row number and select Unhide, this should reveal more rows at the bottom of the page
   4) **Copy and paste all cells in the bottom row of data to the next row down**: Click the number of the last row with information to select the row
   5) Right-Click on the row number and select copy
   6) Click on the number of the next row down
   7) Right Click and select paste
   
**Note: Keyboard shortcuts, such as Ctrl+A, Ctrl+C and Ctrl+V (and their Mac equivalent) do work in replacement of clicking through menus (especially for copying and pasting)**

## Usage with Other Spreadsheet Software
This spreadsheet was designed for use with functionality provided by Excel, which may not be provided in a compatible manner elsewhere. As such, I cannot guarantee it will work with other software, including GoogleⓇ Sheets.

# Known Bugs
* Adding multiple new template pages before renaming the sheet can cause errors

# License
This project is licensed under the GNU General Public License 3.0

    Copyright ©  2020  Benjamin MacDonald

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
    
Full license text is available [HERE][license]
   
   
# Contact
Questions, Issues, and Feedback can be addressed to [Benjamin MacDonald](mailto:benjamin@networkalliance.ca?subject=[GitHub]%20Speed%20Tracker%20)

[license]: https://github.com/Quantum158/Speed-Tracking/blob/master/LICENSE
