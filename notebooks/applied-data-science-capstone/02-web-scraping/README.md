# This folder contains the completed Webscraping lab. I found an error in the extracted portion of the lab and pasted here in this section of the readme
## extracted_row = 0
           - # Customer
           - # TODO: Append the customer into launch_dict with key `Customer`
           - # STUDENT COMMENT: We get an error here with this ==> customer = row[6].a.string, So I added the next line below
           - customer = row[6].get_text(strip=True)
           - launch_dict['Customer'].append(customer)
           - #print(customer)
