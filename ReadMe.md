# JQuey

## Rules  

--> Need to include Jquery file or CDN in HTML
--> Start with or without Jquery Starter Code
    
    $(document).ready(function({
        ====code in here====
    }))

--> $("id/class/selector").css("css property", "value")

    $("#test").css("color", "green")

--> can select multiple id/class, Example

    $("#id, .id, #id ...").css("color", "green")

## Jquery examples and documentation

1. css Styling


Examples--> 

* $("#test").css("color", "green")
* $(".test").css("border", "2px dotted red")
* $("*").css("border", "3px solid red")
* $("li:first-child").css("color", "green") 
* $("ul li:eq(3)").css("color", "green")
* $("ul li:gt(1)").css("color", "red")
* $("ul li:lt(3)").css("color", "red")

2. Mouse click Event, Examples

--> click Event

$("#box").click(function(){
        $("#box").css("background-color", "blue")
    })

--> Double Click Event Example

    $("#box").dblclick(function(){
        $("#box").css("background-color", "skyblue")
    })

--> Contextmenu, Mouse Right click event

    $("#box").contextmenu(function(){
        $("#box").css("background-color", "skyblue")
    })

--> Other(s): mouseenter (when mouse enter into event area)

3. Keyboard Event

--> Keypress, any key press event

    $("body").keypress(function(){
        $(this).css("background-color", "green")
    })

--> other(s):  keyup, keydown

4. Form Event

--> focus, focus the area and content

    $("#name").focus(function(){
        $(this).css("background-color", "green");

--> change, Live value update

    $(".country").change(function(){
        var a = $(this).val()
        $("#input").html(a);

--> other(s): Blur

5. Window Event