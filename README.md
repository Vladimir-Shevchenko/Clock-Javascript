# Clock-Javascript
Clock with setInterval


function clock(){
 var date = new Date(),
 hours = (date.getHours() < 10) ? '0' + date.getHours() : date.getHours(),
 minutes = (date.getMinutes() < 10) ? '0' + date.getMinutes() : date.getMinutes(),
 seconds = (date.getSeconds() < 10) ? '0' + date.getSeconds() : date.getSeconds();
 console.log(hours + ':' + minutes + ':' + seconds);
}
setInterval(clock, 1000);
1
2
3
4
5
6
7
8
function clock(){
    var date = new Date(),
        hours = (date.getHours() < 10) ? '0' + date.getHours() : date.getHours(),
        minutes = (date.getMinutes() < 10) ? '0' + date.getMinutes() : date.getMinutes(),
        seconds = (date.getSeconds() < 10) ? '0' + date.getSeconds() : date.getSeconds();
    console.log(hours + ':' + minutes + ':' + seconds);
}
setInterval(clock, 1000);
