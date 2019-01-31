# This contains methods of table class in python gauge 
Table methods from gauge:
1> headers
  :: Syntax: table.headers
  :: Returns: the header of the table(table header)
	:: example => ['Word', 'Vowel Count']


2> rows : use as ::: table.rows
	returns list of list of each rows of the table as giver
		[['Gauge', '3'], ['Mingle', '2'], ['Snap', '1'], ['GoCD', '1'], ['Rhythm', '0']]
		where each list represent a row of the table
    
3> get_row(index)
       :: syntax => table.get_row(1)
	=>get the first row of the table

4> get_column_values_with_name("name_of_column")
	:: syntax => table.get_column_values_with_name("name")
	::=> return all the values(data) of the column with header name

5> get_column_values_with_index(index)
	:: synatax =>  table.get_column_values_with_index(1)
	::=> returns all the data from the first column i.e column 1

6> __str__
7> __eq__(other)
8> __getitem__(i)
9> __iter__

// Available methods in DataStore class:
1> get(key)
2> put(key, value)
3> is_present(key)
4> clear()
5 __eq__(other)
