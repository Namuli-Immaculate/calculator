# calculator
 A JavaScript program that prompts a user to enter the user's year of birth and in turn prints a string in the console stating whether the user is a minor, a youth or an elder. Anyone below 18 years is a minor, anyone between 18 and 36 years of age is a youth and the rest are elders.
 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Age Calc</title>
</head>
<body>
    <h1>Age Calculator</h1>
    <script>
let year= parseInt(prompt('Enter your birth year'));
let age=(2019-year);
if(age<18){
    console.log('You are a minor')
}else if(age>18 && age<36)
{
    console.log('You are a youth')
}else{
    console.log('You are an elder')
}
    </script> 
</body>
</html>
