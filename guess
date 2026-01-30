const minNum=1;
const  maxNum=100;
const answer =Math.floor(Math.random()*(maxNum-minNum)+minNum);
let attempts=0;
let guess;
let running=true;
 
while(running){
    guess=window.prompt(`Enter the number between ${minNum}  and ${maxNum}`);
    guess=Number(guess);
    if(NaN(guess)){
        window.alert("enter the valid Number");

    }
    else if(guess<minNum || guess>maxNum) {
        window.alert("Enter the Number between Proper Range");

    }
    else{
        attempts++;

        if(guess<answer){
            window.alert("Too low");
        }
        else if(guess>answer){
            window.alert("Too high");
        }
        else{
            window.alert(`You Have Guessed The Numebr at ${attempts} attempts.`);
        }


    }
}
