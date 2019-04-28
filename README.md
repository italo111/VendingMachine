# VendingMachine

Project Objectives:

Develop a Vending machine using the board  Elbert V2 – Spartan 3A, and its internal components. The project uses a single display that shows the price of the 4 different beverages that are on sale.  4 led positions that show where each different types of beverage are located. 3 switches that represent the different coins inserted into the vending machine. A reset button to go back to initial conditions at any moment, in this case is switch 6. A start button (switch 4) that allows a person to select the different drinks available. A back button that allows the user to make another selection after a drink has already being selected. 3 single pole switches that are used for the selection of 4 beverages.
Description:
The vending machine consist of 4 different types of drinks ( Pepsi, 7Up, Fanta, Coke)  the drinks are located horizontally in 4 columns. When coke is dispensed then led1 lights up, when fanta is dispensed then led2 lights up, when 7up is dispensed then led3 lights up, and when Pepsi is dispensed led4 lights up. To select the different drinks with the single pole switches from 000 selects coke, 001 selects fanta, 010 selects 7Up, 011 selects Pepsi.
All drinks have different prices, and when you insert a coin the display shows the amount inserted so far.
The prices are as follows: coke is $1, Fanta is $3, 7Up is $2, Pepsi is $1.

Components Used:

FPGA board ( one bcd display, 4 leds, 6 push buttons, 3 single pole switches)

