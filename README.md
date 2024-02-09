# Mini-Animals-Project-Using-JS

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <title>Small animal mini project</title>
</head>
<script>
    function animal() {
        let an = document.getElementById("a").value;
        document.body.style.backgroundColor="#66ff99";

        switch (an) {
            case 'tiger':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm Tiger</h1>" +
                "<img src='pictures/tiger.avif' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/angry-tiger-6089.mp3'></audio></div>";
                break;


                case 'lion':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm lion</h1>" +
                "<img src='pictures/lion.webp' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/lion-roar-6011.mp3'></audio></div>";
                break;


                case 'cat':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm Cat</h1>" +
                "<img src='pictures/cat.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/cat-98721.mp3'></audio></div>";
                break;


                case 'dog':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm dog</h1>" +
                "<img src='pictures/dog.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/dog-barking-70772.mp3'></audio></div>";
                break;


                case 'giraffe':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm giraffe</h1>" +
                "<img src='pictures/giraffe.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/squeaky-giraffe-toy-to-eat-22550.mp3'></audio></div>";
                break;


                case 'sheep':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm sheep</h1>" +
                "<img src='pictures/sheep.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/sheep-122256.mp3'></audio></div>";
                break;


                case 'goat':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm goat</h1>" +
                "<img src='pictures/goat.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/goat.mp3'></audio></div>";
                break;


                case 'elephant':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm elephant</h1>" +
                "<img src='pictures/elephant.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/elephant.mp3'></audio></div>";
                break;

                case 'rabbit':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm rabbit</h1>" +
                "<img src='pictures/rabbit.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/rabbit-oinks-and-squeaks-71608.mp3'></audio></div>";
                break;

                case 'horse':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm horse</h1>" +
                "<img src='pictures/horse.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/horse-123780.mp3'></audio></div>";
                break;

                case 'deer':
                document.getElementById("result").innerHTML = "<div class='text-center'><h1>Hello, I'm deer</h1>" +
                "<img src='pictures/deer.jpg' alt='Tiger' width='500'>" +"<br>"+
                "<audio controls autoplay src='audio/cute-animal-squeak-1-188097.mp3'></audio></div>";
                break;

                delete
                alert("invalid");
                break;
        }
    }
</script>
<style>
    .a {
        margin-top: 50px;
    }
</style>
<body>
    <form class="a">
        <center>
            Enter animal <input type="text" id="a">
            <button type="button" onclick="animal()" class="btn btn-primary">Submit</button>
        </center>
    </form>
    <div id="result"></div>
   
</body>
</html>
