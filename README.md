# Unit-Converter

unit_dict = {'meters': .3048, 'miles': 1609.34, 'kilometers': 1000}
unit_type = input("Would you like to convert to meters, miles, or kilometers?\n:")
while unit_type not in unit_dict.keys():
    unit_type = input("Would you like to convert to meters, miles, or kilometers?\n:")
feet_input = int (input("What is the distance in feet?\n:"))
meter_output = feet_input * unit_dict[unit_type]
print("Thank you. " + str(feet_input) + " feet is equivalent to " + str(meter_output) + " " + unit_type)
