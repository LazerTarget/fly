<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Email redirection</title>
    <style>
        body
        {
            background-color: #FCFDF2;
        }
        .caution
        {
            font-size: 18px;
        }
        input [type="submit"]
        {
            border: 2px solid red;
            border-radius: 4px;
        }
        #mail
        {
            background-color: #e11313;
            padding: 1%;
            border-radius: 15px;
            border-color: white;

            font-size: large;
            border-width: 3px;
            color: white;
            width:100px;




        }

        .main
        {
           font-size: 20px;

        }
        h1
        {
           color: #400D51;
           text-decoration-line: underline;
           margin-bottom: 2%;

        }
        div{


        }
        span
        { 
           border-color: #400D51;
           border-width: 1px;
           border-right-width: 2px;

        }
        p{
            border-top: 20px;
        }
    </style>
</head>
<body>
    <div>
    <center>
    <span><h1>Email Redirection</h1></span>
    </center>
</div>
    <hr>
    <p class="main">⇢The purpose of this website is to help you send the mail to DOSA with just one click.</p>
    <ul class="caution">

        <li>Clicking on submit button will redirect you to your default mail browser. </li>
        <li>The message to be sent will be copied to your text area.</li>
        <li>Make sure to use your <strong>thapar id</strong> to send the mail</li>

    </ul>
    <hr>
    <form action="mailto:dosa@thapar.edu" method="post" enctype="text/plain">
        <label for="mail" id="label"><strong></strong></label>
        <center>
        <input type="submit" name="We, first-year students, deeply feel that our personal and career growth is being hindered due to our overloaded college classes schedule. Most of the days, we attend classes from early morning till evening. The mental stress and lack of free time for learning new skills as engineers-in-making is taking a toll on us. It also reduces the amount of time we can devote to getting good grades. So we humbly request you to cancel all classes on all Saturdays for First-years." id="mail" >
    </center>

    </form>

</body>
</html>
