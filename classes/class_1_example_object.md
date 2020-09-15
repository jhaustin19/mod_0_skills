Object: Server

Attributes:
name: 'John'
weekly_schedule: {}
floor_section: _NULL_
hourly_pay: 2.5

Methods:
print_name_tag: puts 'John'
set_weekly_schedule: weekly_schedule = {
  'mon': 'off',
  'tues': 'early',
  'wed': 'early',
  'thurs': 'late',
  'fri': 'double',
  'sat': 'off',
  'sun': 'off'
}
set_floor_section: floor_section = 4
pay_day: puts '#{2.5 * (6 + 6 + 6 + 12)}'
