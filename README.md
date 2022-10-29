# Typescript
12/10/2022: Angular(softwares,versions)

1.Install vscode & node.js                                         
2.node-v (node.js version)                                                  
3.npm-v (Node Package Manager(npm)version)                    

4.open vscode 
     |
  Create a folder and name it 
     |
  Copy the path of folder
     |
  open vscode-cmd-paste the path
     |
 angular installed

5.Installation of angular project:
   open vs code in admin mode
       |
   Terminal-new terminal in cmd
       |
   a.npm install-g@angular/cli 
       |
   b.ng new my-app (project name of angular)
       |
   c.cd my app (cd-change directory)
       |
   d.ng serve (to open the project)

Node.js is a open source,server-side backend

[npm with node.js by default manages project dependencies].

[cli-command line interface used to build angular app by automatic operations rather than manually])
        
          ====================================================================

14/10/22:

   URL-Uniform Resource Locator -Specifices where a unique resource can be found on the internet.
     
     http://localhost:4200
      |        |       |
     client  local    Port
     server  Address
   
  Q.What is port and what happens multiple projects run at a time with same port ?
    
    It identifies a service provided by an application.
    Same port number is not used for different applications.Error will be detected.


Routing: changes the path/selecting a path across one or more networks.
   
           ============================================================================
 17/10/22: 
  
 Folder Structure of Angular project:
 
 a.e2e: end to end testing--used for testing the user behaviour on server.
 b.node_modules folder: containes the folders which are installed into our application when created a project.
 c.src: source code of angular application 
 d.package.json: imp for every npm project. contains basic information software vesrion,dependencies which are in use
 e.package-lock-json: no new versions will be updated to run the project.runs on older versions.
 f.editorconfig file: used to set up team environment with standard rules followed by developers.
 g.gitignore file: ignores in the git repository.
 h.angular.json file: contains configuration of project.replaced angular-cli.json.
 i.browserslist: used by autoprefixer to adjust css to suport the specified browsers.
 j.test.js & karma.config.js: used for testing purposes.
 k.README.mdfile: contains description of project which we like to give to end user so they can start using app in great way.
 l.ts config.app.json: used during compilation of application & contains configuration information.
 m.tsconfig.json:contains configuration for typescripts.
 n.tsconfig.spec.json: used for testing purpose in node.js , helps in maintaing the details for testing.
 o.tslint.json:used for maintability , functionality and readability errors for typescript code.
 src folder:
 Contains subfolders and files
 a.app folder:files created by deafult in this when we create an ng application.
 b.assets: we can store static assets like images,icons etc..,files, which needs to be copied while building application,
 c.environments:to store environment, specific configuration of database credentials or server adress.
 d.favicon.ico: icon displays on browser.
 e.index.html:Contains html code with head and body section.
 f.main.ts file:entry point for our angular application.
 g.polyfills.ts: used for browser related configuration,also used by compiler to compile ts code to specific js method
                 fill the gap to provide js features needed by angular and supported by latest version.
 h.spect.ts:just for inspection.
 i.app module: ng application itself ia module,
               used to launch or build the code of application.
               Any functionality can be made into a chunks.
 j.app.module.js: bootstrap ha its component which has a logic code and reference to html, css.
 k.app.componets:contains all components code for controlling its functionality.
 l.routing.module.ts:contains routing configuration.
                     purpose is to load & configure the router in a seperate file or for readability.

Bundling and minification:

2 imp process that angular adopts to reduce the size of application
minification: removes white spaces,unwanted variable within file,
              conatins big variable names to smaller variable names.
       ==============================================================================
18/10/2022:

Typescript:
 
> Superset of javascript
> Helps programmers to write object oriented programs and have compiled to js both server and client side.
> easy to use,build application faster,good tooling support.

Q.Diff b/w typescript and javascript?

    typescript: datatype is fixed,detect the error immediately.code maintaince,easier to learn,static typing
    javascript: datatype is not fixed.it will run the code and later it detects the error,has dynamic typing.
 
Q.why ts?

 because it has types.js has no types.

    Datatypes--Every value or data has an associated type nothing but datatype.
               Determines how the value or data can be used in programm.

    a.String--Enclosed with ""  eg;"123"
    b.integer--Any number       eg;1,2,0,-1,-2
    c.Float--decimal number     eg:1.0, 20.3
    d.Boolean--True or False
    e.enums
    f.objects,
    g.void--use to represent non returning functions.

**Control statements: 

Changes the flow of execution of statements

1.conditional statements,
2.loops,
3.continue,break

1.conditional statements:-

In control statements we have lots of conditional statements like

a.if,else if, and----decision making 

  eg.,amazon, flipkart

  if(price=51,000 and color=blue and memory=128gb and deliveryin = 2 days)

  order from amazon

  else if (price=49,000 and color=blue and memory=128gb and deliveryin = 7 days)

  order from flipkart

  else

  order from chroma

b.switch cases---(this or that) 

  directly placing the order
  
  case 1: price=51,000 and color=blue and memory=128gb and deliveryin = 2 days

  order from amazon 

  case 2: price=49,000 and color=blue and memory=128gb and deliveryin = 7 days 

  order from flipkart 

  default: 
  
  order from chroma

2.Loops:-

 doing the same activity so many times 

  a.for loop

  b.while loop 

  c.do while

a.for loop:-

  eg.,Sum of n natural numbers using for loop 

   var sum = 0;
   const n = 100
   for(var i=1;i<=n;i++){
   sum = sum + i
   }
   console.log(sum); 

  ouput: 5050
        
          ========================================================================

19/10/2022: 

 for loop--

 for(initial value;termination_condition;steps/incrementals/step by which value should incrementation.

 while--

 initial condition-steps/incrementals/step by which value should incrementation.

 eg.,if(i<=100) then while is stoped.

 do while--
 first do{} then while(condition) is executed.

>Javascript and typescript programmes are executed in synchronous way.i.e.,step by step.

           ====================================================================    

**Functions:-

for doing the repetative tasks functions are used

eg:,chat(true/false){

    if(true)--run html

    else--donot run html

    }
    
    In the above,true/false are arguments.

To run the functions we have to give some parameters/argumnets.

 eg.,human (it is function)
      |
    first name,last name,age etc.,(these are parameters/arguments)

write a function for sum of two numbers..?

function_name(parameter1 + parameter2){

logic(parameter1+parameter2);

}

In functions we have

arrow function:- ()=>

we use arrow function becoz these are "short hand syntax".
                                              |
                                     major advantages of ts.
                                              |
                                    no need to write full function just we can give ()=>
function types:-

a.void

b.return

a.void--non-retunable.it does not return any value,its just execute the logic.

b.return--it executes the logic and returns the value.

         ================================================================================================================

21/10/22:

functions cont..

syntax: var/let/const/readonly.

1.var name.of function:

      function(passing arguments){

     }

2.short hand syntax

  var func_name=()=>{

  ..condition/logic

 } 

Typescript supports short hand syntax.

function has parameters which are also called function signatures.

a.parameterless function

b.parameter function

a.parameterless function: It means function without arguments.

    eg., var order=()=> {

         //conditions.logics.iterations.

         console.log("Hi vaishnavi order place,thank you!")

         } 
     
         order();  --------function must be called to get output.

         output:-"Hi vaishnavi order placed,thank you!"

b.Parameter function: It means function with arguments.

    eg.,var getItems=(id:number,name:string){           

        console.log("Hey" +name+ "welcome back,please place your orders and your userId is "+id);

        } 

        getItems(321,"Vaishnavi");     }------Only 2 arguments called becoz we have given only 2 arguments in function.
        getItems(123,"venkat");        }
   
        output:--Hey Vaishnavi welcomeback, please place your orders and your userId is 321
                 Hey venkat welcomeback, please place your orders and your userId is 123
       
        code is reusable in parameter function


      --Parameter can be string/number.ie.,(id:number|string, name:string).   

Booking tickets with return function:-

         var bookTickets = (cinema:string): string)=>{

             var ticketnumber="1234"+cinema
 
             return ticketnumber; 

         var userVaishnavi = bookTickets("Vikram");
         var userVenkat = bookTickets("Major");  

         Console.log("Hello, vaishnavi...Your booked ticketInformation",userVaishnavi);
         Console.log("Hello, vaishnavi...Your booked ticketInformation",userVenkat);    

         ouput;-Hello,Vaishnavi...Your booked ticketInformation,1234Vikram
                Hello,Venkat...Your booked ticketInformation,1234Major 


         Functions are using in different ways by passing different parameters.

         Functions are also called methods.

          ================================================================================================

**setting up typescript in visual studio code:--

  1.Open cmd and install the typescript-->npm install-g typescript
  2.check the version-->tsc--version
  3.open vscode-->select a folder and create a file with .ts extension
  4.Create a tsconfig file ? tsc cmd --init
  5.convert a typescript file to javascript ? tsc {file_name}--> Creates a javascript file with the same name as {file_name}
  6.Run the generated JS Code using ---> node learn_tsc.js  

**Arrays:-

  Array is continous memory.Arrays are list of items in a similar pattern.It means array has similar(linear) data types.
  These have numbers, strings,objects..etc
 
  eg.,super markets
      crackers
      clothes
Array  can declared has []

var supermarket = ["sugar","oil","salt"];
    console.log(supermarket[1])
    Ouput:-oil

Numbering is given from 0 in programming languages.

eg.,["sugar","oil","salt"];
       0        1    2

Array length is 3 , Array size is 2.Array has indexes.Indexes are the identifiers of the element.

push--we add the items inside array 
pop--We can delete the items inside array

Inbound & Outbound:-

Inbound->Indise Array range . Will fetch the  records within the length and size
outbound->Outside of array limits.Undefined


once Type of array is defined we cannot assign another datatype to the array.

**objects:-

 nothing but self contained components consists of properties.

 eg.,cup--its has own shape,colour,weight,height,design.

**Classes:--

 Nothing but bluprint of objects.Object has its own properties.classes defines the behaviour of objects.

 syntax:-properties,constructors,methods

 eg.,class customers{ 
           age:string;
           name:string;
           product_used_by_customer:string;

           constructor()
           {
            this.age = "20";
            this.name = "Vaishnavi";
            this.product_used_by_customer = "oneplus";
           }

           printCustomerDetails(a:string,b:string,c:string){
           console.log("These are the details that you have requested for",this.age,this.name,this.product_used_by_customer)
           }
           }
  **constructors:-
               
    Nothing but starting point of a class.Setting a default value.  
