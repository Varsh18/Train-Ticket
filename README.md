A Train Ticket booking application developed using C++ and Database as File.


The program first present a menu with following options:
1.Book Ticket
2.Cancel Ticket
3.Print All
4.Print Availability
5.Exit


#Details and Conditions that are common

1.The train has only one coach with 16 berths (4 Lower,4 Middle,4 Upper,2 Side Upper and 2 Side Lower)
2. 14 Confirmed tickets will be allotted a berth (4 Lower,4 Middle,4 Upper,2 Side Upper)
3. The remaining 2 Side Lower berths are issued as 4 RAC tickets (Reservation Against Cancellation)
4.No ticket for infants below 5 years of age
5. Wait list tickets should be issued for bookings beyond the confirmed 14 and 4 RAC. There can be only 2 waitlist tickets.



#Book Ticket
1.When Book Ticket is chosen
     It should prompt for the passenger details like:
                       Enter Name:
				Enter Age:
				Enter Preference:
				Do you want to book one more? (Y/N):
     Kids/Infants below the age of 5 should also be accepted the same way.
     After entering the details of all the passengers in the group, it should print the ticket.


2.Conditions for booking a ticket
      When no berth preference is given for a passenger, the following rules should be applied:
       Passengers with kids should be given a lower berth.
       Passengers with age >60 should be allotted a lower berth, if available.
