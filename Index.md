<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Snowday Predictor</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Comfortaa:wght@300..700&family=Quicksand:wght@300..700&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
        <link rel= "stylesheet" href= "dist/css/style.css">
        <script src="Functions.js"></script>
    </head>
<body>
    <main>
        <section class="paymentContainer" style="background-color: #ecf4fe; padding: 5px; border-radius: 20px;">
            <div class="sectionContainer" id="camera">
                <span class="recent-text">Locations</span>
                <select size="2" id="sessions" onchange="switchSession()" style="font-family: 'Montserrat', sans-serif; padding: 15px;border-radius: 10px; outline: none; border: none; border-width: 0; max-width: 100%; height: 90%; display: block; width: 100%; background-color: #e0efff; color: black;">
                    <option selected="selected" value="0">Automatic</option>
                    <option value="1">Ottawa</option>
                    <option value="2">Montreal</option>
                    <option value="3">Toronto</option>
                    <option value="4">New York</option>
                    <option value="5">Boston</option>
                    <option value="6">San Francisco</option>
                    <option value="7">Los Angeles</option>
                </select>
            </div>

            <div class="sectionContainer" id="chat">
                <!-- <div class="chat-container"> -->
                    <div class="percentage-text" id="percentage-text"></div>
                    <div class="container" id="chatbox">
                        <span style="--meter-value: 75;" class="progress-bar" id="progress-bar"></span>
                        <!-- <div class="textbox" placeholder="Enter Answer" onkeydown="checkEnter(event)"> -->
                        <!-- <div style="position: relative; display: inline-block; cursor: pointer;" onclick="startLoading()">                                  -->
                    </div>
                <div class="table-holder">
                    <table class="weather-info">
                        <tr id="dow">
                        </tr>
                        <tr class="table-elements" id="chance"> 
                            <td class="column-elements" >
                                <div id="chance-element-1">Snow day chance</div>
                                <div class="chat-container">
                                    <div class="container" id="daily-scale">
                                        <span style="--meter-value: 75;" class="progress-bar" id="progress-bar-1"></span>
                                    </div>
                                </div>
                            </td>
                            <td class="column-elements" >
                                <div id="chance-element-2">Snow day chance</div>
                                <div class="chat-container">
                                    <div class="container" id="daily-scale">
                                        <span style="--meter-value: 75;" class="progress-bar" id="progress-bar-2"></span>
                                    </div>
                                </div>
                            </td>
                            <td class="column-elements" >
                                <div id="chance-element-3">Snow day chance</div>
                                <div class="chat-container">
                                    <div class="container" id="daily-scale">
                                        <span style="--meter-value: 75;" class="progress-bar" id="progress-bar-3"></span>
                                    </div>
                                </div>
                            </td>
                            <td class="column-elements" >
                                <div id="chance-element-4">Snow day chance</div>
                                <div class="chat-container">
                                    <div class="container" id="daily-scale">
                                        <span style="--meter-value: 75;" class="progress-bar" id="progress-bar-4"></span>
                                    </div>
                                </div>
                            </td>
                            <td class="column-elements" >
                                <div id="chance-element-5">Snow day chance</div>
                                <div class="chat-container">
                                    <div class="container" id="daily-scale">
                                        <span style="--meter-value: 75;" class="progress-bar" id="progress-bar-5"></span>
                                    </div>
                                </div>
                            </td>
                        </tr>
                        <tr class="table-elements" id="perciptattion-chance">
                        </tr>
                        <tr class="table-elements" id="perciptattion">
                        </tr>
                        <tr class="table-elements" id="wind">
                        </tr>
                        <tr class="table-elements" id="temp"> 
                        </tr>
                        <tr class="table-elements" id="visibility">
                        </tr>
                        <tr class="table-elements" id="uv-index">
                        </tr>
                        <tr class="table-elements" id="visibility">
                        </tr>
                    </table>
                    </div>
                </div>
            </div>
        </section>
    </main>
</body>
</html>