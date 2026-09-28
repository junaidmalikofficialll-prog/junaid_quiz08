# step 1
We created next.js folder by using cmd 
first we open cmd from windows
we write  cd desktop there and then enter
npx create-next-app@latest my name
junaid-sup
after the project is created enter the project folder 
cd junaid-sup

# step 2
insert data in supabase
now we can save our data in note supabase notes table 
The insert() const { data, error } = await supabase from('notes') select('*')

# step 3
in this step we start our project in next.js
run the development server
npm run dev
now we open the address shown in the terminal usually
https://localhost:3000
then we run and show our website result there on localhost:3000

# step 4
go to supabase and login with our account
create a new project and wait for the project to finish our setup

# step 5
in our supabase project we open and 
connect app framework - envirinment etc
then we copy the url of project publish neon/key

# step 6
we use supabase in our next.js page
now supabase can imported to our next.js file
import { supabase } from @lib/supabase
const { data, error } = await supabase from('notes') select('*')

# step 7
insert data in supabase
now we can save our data in note supabase notes table 
we create queries like department, employees, employee attendence
then employee leave request 
insert data employee id, username, email, location

# step 8
in this step 8 we select data from supabase
now we can get the saved notes from database
The select('*') command gets all the data from the notes table 
