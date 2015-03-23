# csv_to_xml_resources
Script to convert a csv file in a android string language resource.

How to use this script?
   You need generate a file csv separating two fields by comma, like this example ahead:
   string_value,string_value #header
   app_name,CSV converter
   app_settings,Settings
   user_name,User Name

Change the script to an executable file:
  \~lpm$ chmod +x csv_xml_language

Executing the script:
	\~lpm$ ./csv_xml_language example_csv_file.csv
