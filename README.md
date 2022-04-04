<DOCTYPE! html>
<html>
    <head>
        <title> GoodForm </title>
    </head>
    <body style="background-color: white">
        <h1> FILL OUT THE FORM </h1>
    <form>
        <div>
            <label for="name"> Name </label>
            <input type="text" name="name" id="name" required>
        </div>
        <br>
        <div>
            <label for="Contact"> Contact</label>
            <input type="number"  required>
        </div>
        <br>
        <div>
            <label for="email"> Email </label>
            <input type="email" name="email" id="email" required>
        </div>
        <br>
        <div>
            <label for="Age"> Age </label>
            <input type="number" name="Age" id="Age" min="1" max="40" required>
        </div>
        <br>
        <div>
            <label for="date"> Birthdate</label>
            <input name="date" type="date" id="date" >
        </div>
        <br>
        <div> Marital status
            <div>
                <label for="single"> single </label>
                <input type="radio" name="Marital status" id="single">
                <label for="Married">
                    Married
                </label>
                <input type="radio" name="Marital status" id="Married">
            </div>
 </div>
 <br>
 <div> Gender
     <div>
         <label for="Male">
             Male
         </label>
         <input type="radio" name="Gender" id="Male">
         <label for="Female">
             Female
         </label>
         <input type="radio" name="Gender" id="Female">
     </div>
 </div>
 <br>
 <div>
     <label for="Why should you be given Admission">
         Why should you be given Admission
     </label>
     <br>
     <textarea></textarea>
     <br>
     <h3> IMAGE </h3>
     <input id="image" type="file">
 </div>
        <br>
        <button type="Reset"> Reset </button>
        <button type="Submit"> Submit </button>
    </form>
  </body>
</html>
