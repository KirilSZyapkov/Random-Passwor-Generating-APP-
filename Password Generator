function randomPassword(num){

    let password = '';
    const upperCase = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ';
    const lowerCase = 'abcdefghijklmnopqrstuvwxyz';
    const numbers = [1,2,3,4,5,6,7,8,9,0];
    const symbols = ["!","@","#","$","%","^","*","(","?","|"];
    const charecters = [upperCase, lowerCase, numbers, symbols];

    const passwordLenght = Number(num);

    for (let a = 0; a < passwordLenght; a++) {
        
        const element = charecters[randomNumber()];
        if(element.length === 10) {
            const symbol = element[randomNumber(10)];
            password+= symbol;
        } else if (element.length === 26) {
            const symbol = element[randomNumber(27)];
            password+= symbol;
        }
    }

    console.log(`Your password is - ${password}`);

}

function randomNumber(a=4){
    return Math.floor(Math.random() * a);
}



randomPassword(15);
