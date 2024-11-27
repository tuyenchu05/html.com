function calculateRectangleArea(){
    var D = parseFloat(document.getElementById('inputD').value); 
    var R = parseFloat(document.getElementById('inputR').value); 

    if (isNaN(D) || isNaN(R) || D <= 0 || R <= 0) {
        alert("Vui lòng nhập chiều dài và chiều rộng hợp lệ.");
        return;
    }

    const S = D * R;
    document.getElementById('outputS').value = S;
}

function calculateTriangleArea(){
    var CD = parseFloat(document.getElementById('inputCD').value);
    var CC = parseFloat(document.getElementById('inputCC').value);

    if (isNaN(CD) || isNaN(CC) || CD <= 0 || CC <= 0) {
        alert("Vui lòng nhập cạnh đáy và chiều cao hợp lệ.");
        return;
    }

    const TG = (CD * CC) / 2;
    document.getElementById('outputTG').value = TG;
}

function calculateSquareArea(){
    var CHV = parseFloat(document.getElementById('inputCHV').value);


    if (isNaN(CHV) || CHV <= 0) {
        alert("Vui lòng nhập chiều dài cạnh hợp lệ.");
        return;
    }

    const HV = CHV * CHV;
    document.getElementById('outputHV').value = HV;
}
