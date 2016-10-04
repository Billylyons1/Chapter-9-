# Chapter-9-
<!DOCTYPE html >
<html>

<head>
    <meta charset="utf-8">
    <title>Contest Entry Form</title>
    <style type="text/css">
        ol,
        ul {
            list-style-type: none;
        }
    </style>
</head>

<body>

    <h1>&ldquo;Pimp My Shoes&rdquo; Contest Entry Form</h1>

    <p>Want to trade in your old sneakers for a custom pair of Forcefields? Make a case for why your shoes have <em>got</em> to go and you may be one of ten lucky winners.</p>
    <form action="http://learningwebdesign.com/contest.php" method="post">
        <fieldset>
            <legend>Contest Entry Information</legend>


            <ul>
                <li><label for="firstlast">Name:</label>
                    <input type="text" name="username" id="firstlast"></li>
                <li><label for="email">Email Address:</label>
                    <input type="text" name="email" id="email"></li>
                <li><label for="state">State:</label>
                    <input type="text" name="state" id="state"></li>
                <li><label for="form-story">My shoes are SO old...</label><br>
                    <textarea name="Story" rows="4" cols="60" maxlength="300" id="form-story" placeholder="No more than 300 characters long"></textarea>


            </ul>
            <h2>Design your custom Forcefields:</h2>

            <legend>Custom Shoe Design</legend>

            <legend>Color <em>(Choose One)</em>:</legend>
            <ul>
                <li><input type="radio" name="Red">Red</li>
                <li><input type="radio" name="Blue">Blue</li>
                <li><input type="radio" name="Black">Black</li>
                <li><input type="radio" name="Silver">Silver</li>
            </ul>

            <p>Features <em>(Choose as many as you want)</em></p>
            <ul>
                <li><input type="checkbox" name="Sparkley laces">Sparkley Laces</li>
                <li><input type="checkbox" name="Metallic logo">Metallic logo</li>
                <li><input type="checkbox" name="Light-up heels">Light-up heels</li>
                <li><input type="checkbox" name="MP3-enabled">MP3-enabled</li>
            </ul>

            <p>Size
                <input type="text" name="Size" </p>
                <p>Sizes reflect standard men's sizes:</p>

</body>

</html>
