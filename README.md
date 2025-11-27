# JS-Basics

HTML
    <button id="add-btn">Log Value</button>


JS
//getElementById: call it from HTML
 const addButton = document.getElementById("add-btn");

//create new li <li><li>
 const li = document.createElement("li");


const delBtn = document.createElement("button");
//.textContent: give new value to delBtn <button>"Delete"<button>
    delBtn.textContent = "Delete";

//appecChild: add delBtn to li
    li.appendChild(delBtn);



