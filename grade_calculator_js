function checkgrade(evt) {
  let grade =parseFloat(evt.currentTarget.value);

  if (grade > 100 || grade < 0) {
    console.log("Wrong value")
    evt.currentTarget.style.color = "red"
  } else {
    console.log("Correct Value")
    evt.currentTarget.style.color = "black"

  }

}

function calculategrade(){

  let homework_percent = parseInt(document.getElementById("homeworkpercent").innerHTML)

  let homework_grade = parseFloat(document.getElementById("homeworkgrade").value)

  let quiz_percent = parseInt(document.getElementById("quizpercent").innerHTML)

  let quiz_grade = parseFloat(document.getElementById("quizgrade").value)

  let attendance_percent = parseInt(document.getElementById("attendancepercent").innerHTML)

  let attendance_grade = parseFloat(document.getElementById("attendancegrade").value)

  let project1_percent = parseInt(document.getElementById("project1percent").innerHTML)

  let project1_grade = parseFloat(document.getElementById("p1grade").value)

  let project2_percent = parseInt(document.getElementById("project2percent").innerHTML)

  let project2_grade = parseFloat(document.getElementById("p2grade").value)

  let calculategrade = homework_percent * homework_grade/100 + quiz_percent * quiz_grade/100 + attendance_percent * attendance_grade/100 + project1_percent * project1_grade/100 + project2_percent * project2_grade/100          
  console.log(calculategrade)

  document.getElementById("cgrade").innerHTML = calculategrade
  
}
