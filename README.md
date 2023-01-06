Extra Things

// function showingWatchlistData(responseLatestOpen, responseSymbol) {

//     watchlistName.innerText = responseSymbol;
//     watchlistScore.innerText = responseLatestOpen;
//     watchlistSelect.innerText = clickedValue;
// }



// btnCross.addEventListener('click', crossfunc)
// function crossfunc(){
//     containerWatchListDetails.style.display = 'none';

//   
// 
// }
// holderDomElement.addEventListener("click", (e) => {
//     if (e.target.classList.contains("btn-cross")) {
//         const targetedLi = e.target.parentNode.parentNode;
//         // targetedLi.remove();
//         targetedLi.innerText = '';
//         console.log("removeeee")
//     }
//     if (e.target.classList.contains("fa-xmark")) {
//         const targetedLi = e.target.parentNode.parentNode.parentNode;
//         // targetedLi.remove();
//         targetedLi.innerText = '';
//         console.log("removeeee")
//     }
//     if(e.target.classList.contains("watchlist-select")){
//         const targetedTable = e.target.parentNode.parentNode;
//         console.log("TABLEEEEEEE")
//         creatTable();
//     }


// });



// const clickedFunc = (e) => {
//     //console.log(e.target.innerText);
    
//     if (e.target.innerText == btnIntraday.innerText) {
//         clickedValue = e.target.innerText
//         console.log(clickedValue);

//     } else if (e.target.innerText == btnDaily.innerText) {
//         clickedValue = e.target.innerText;
//         console.log(clickedValue);
//     } else if (e.target.innerText == btnWeekly.innerText) {
//         clickedValue = e.target.innerText;
//         console.log(clickedValue);
//     } else if (e.target.innerText == btnMonthly.innerText) {
//         clickedValue = e.target.innerText;
//         console.log(clickedValue);
//     } else {
//         clickedValue = btnIntraday.innerText;
//         console.log(clickedValue);
//     }

//     return clickedValue;
// }

// btnIntraday.addEventListener('click', clickedFunc)
// btnDaily.addEventListener('click', clickedFunc)
// btnWeekly.addEventListener('click', clickedFunc)
// btnMonthly.addEventListener('click', clickedFunc)

// console.log(clickedValue)




// let symbol = document.getElementById('symbol-input')
    // symbol = symbol.value
    // console.log(clickedValue)
    // console.log(symbol)