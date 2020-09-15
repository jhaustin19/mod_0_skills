Class: Server

Attributes:
* name (string)
* weekly_schedule (hash)
* floor_section (integer)
* hourly_pay (float)

Methods:
* print_name_tag (At the start of a shift, prints a name tag for employee to wear using attribute _name_)
* set_schedule (At the beginning of the week, updates _weekly_schedule_ with employee's schedule for the week)
* set_floor_section (Sets _floor_section_, integer indicating which section of the restaurant the employee will be servicing)
* pay_day (Uses _hourly_pay_ and _weekly_schedule_ to pay the employee for time worked)
