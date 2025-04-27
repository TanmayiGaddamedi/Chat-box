# Chat-box
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Chat Interface</title>
    <style>
        body {
            font-family: Arial;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; 
            margin: 0; 
        }

        .chatbox {
            width: 400px;
            height: 600px;
            border: 1px solid #ddd;
            display: flex;
            flex-direction: column;
            margin-top: 20px;
        }

        .header {
            background-color: #2d07b9;
            color: white;
            padding: 10px;
            display: flex;
            align-items: center;
            border-bottom: 1px solid #111010;
        }

        .messages {
            flex: 1;
            background-color: #f1fade;
            padding: 10px;
            border-bottom: 1px solid #1a1717; 
        }

        .input-area {
            padding: 10px;
            display: flex;
            border-top: 1px solid #110f0f; 
            background-color: #f9f9f9;
        }

        input {
            flex: 1;
            padding: 8px;
            border-radius: 20px;
            border: 1px solid #4d13c9;
            margin-right: 10px;
        }

        button {
            background-color: #5b0bee;
            color: white;
            border: none;
            padding: 8px 12px;
        }
    </style>
</head>
<body style="background-color:antiquewhite ;">
    <div class="chatbox">
        <div class="header">
            <img src="ava.jpg" style="width: 40px; height: 40px; border-radius: 50%; margin-right: 10px;">
            <div>
                <h4 style="margin: 0;">Sadhvitha</h4>
                <p >Last seen today at 1:15 PM</p>
            </div>
        </div>
        <div class="messages">
            <div style="display: flex; margin-bottom: 10px;">
                <img src="sender.jpg" style="width: 30px; height: 30px; border-radius: 50%; margin-right: 10px;">
                <div style="background-color: #fff; padding: 10px; border-radius: 10px; max-width: 60%; box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);">
                    Hi Tanmayi! How are you?
                    <div>1:20 PM</div>
                </div>
            </div>

            <div style="display: flex; justify-content: flex-end; margin-bottom: 10px;">
                <div style="background-color: #dcf8c6; padding: 10px; border-radius: 10px; max-width: 60%; box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);">
                    Hey! I am good. How about you?
                    <div>1:22 PM</div>
                </div>
                <img src="user.jpg" style="width: 30px; height: 30px; border-radius: 50%; margin-left: 10px;">
            </div>
        </div>

        <div class="input-area">
            <input type="text" placeholder="Type a message">
            <button>Send</button>
        </div>
    </div>
</body>
</html>
