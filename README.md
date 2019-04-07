# Simple-repair-system-for-a-car-repair-shop
Project for Java course (Technical University of Crete)

Design and develop Java programming language
a simple repair system for a car repair shop. The workshop
is described by:
1. the name and surname of the owner (you think there is only one owner);
2. its address (street, number, city),
3. his phone.
Employees are employed in the workshop. Every employee is described by:
1. a unique code number for each employee. This code should not
is requested by the user but will be automatically given by the system.
2. his surname,
3. the price charged by the worker for labor costs per hour.
The workshop provides repairs to vehicles. Each vehicle is described by:
1. its plate number,
2. the surname of the owner,
3. the phone of its owner.
Each repair is characterized by:
1. the vehicle in which it was carried,
2. the date on which,
3. a set of operations (eg, dyeing, oil change etc.) carried out, duration to
hours of each job and the worker who performed the work. You think
that a repair will not contain more than five (5) jobs.
4. The total cost of spare parts used.
Each task is described by:
1. Its name
2. The code number, which is unique to each job and is given by
the system.
The system you plan and implement should provide the following functions:
1. Enter workshop data (suppose there is only one workshop). When the
user selected crew import, will give his details.
2. Introduction of work. When the user selects a job entry, it will provide the data
work.
3. Introduction of a worker. When the user chooses an employee entry, they will give the employee details.
4. Vehicle introduction. When the user selects a vehicle input, he will give the data
of the vehicle.
5. Introduce repair. When the user chooses the introduction of a new repair he will give
the components of the repair, that is, will choose:
◦ from the list of available tasks, one or more tasks, as well as
duration of each job,
◦ from the list of employees, the employee who carried out each job.
If the worker does not exist, an appropriate error message should be generated.
◦ from the list of vehicles, the vehicle to be repaired. If the vehicle is not
there should be an appropriate error message.
6. Deleting work, worker, vehicle, repair. The user will choose from
the corresponding item list (work, worker, vehicle, repair) that he wants to delete.
7. Finding repairs and printing their data based on:
(a) the plate number of the vehicle in which they were or
(b) the extent to which repairs were carried out. For example, he repaired all repairs carried out from 10.03.2014 until 10.04.2014.
(c) the cost of all repairs when this is above a limit provided by the
user. For example, he printed all repairs at a cost of more than 1000 euros. The
the cost of a repair is equal to the cost of the spare parts used,
plus the cost for each job (depends on the duration of the job and its charge)
worker who made it per hour).
8. Print the data of all works, or workers, or vehicles, or of
repairs
