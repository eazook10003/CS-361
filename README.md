# CS-361
Clear instructions for how to REQUEST data from the microservice you implemented. Include an example call.
- I am process the data using javascript and AJAX. 
- Then create a variable and converts into a JSON format.
- Then create a dictionary 
- The section starting with ” $.ajax“, creates the JSON and readies it to be passed to “/test” identified in

                    Example code
//*******************************************
    const dict_values = {count} // count stores the number of likes
    const s = JSON.stringify(dict_values);
    $.ajax({
        url:"/test",
        type:"POST",
        contentType: "application/json",
        data: JSON.stringify(s)});
    })
*****************************************//


Clear instructions for how to RECEIVE data from the microservice you implemented
- output = request.get_json() //example call
- Revieves the data from javascript and store in a new variable 
- methods=[‘POST’] -> This is what it is looking out for when the JSON is been sent.

Source: https://dataanalyticsireland.ie/2021/12/13/how-to-pass-a-javascript-variable-to-python-using-json/

UML sequence diagram showing how requesting and receiving data work. Make it detailed enough that your partner (and your grader) will understand<img width="618" alt="Screen Shot 2022-07-25 at 10 46 14 AM" src="https://user-images.githubusercontent.com/82238220/180677634-e91049cc-f1c4-4871-9501-e43071c45a35.png">
