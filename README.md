# JQuery

Combining Events With Selectors :

Console Check - 

Input : $("#output div:last").show();
Output : div.shape.circle.red

Input : $("#output div:last").hide();
Output : div.shape.circle.red

Input : $("#output div:last").hide().show();
Output : div.shape.circle.red

Input : $("#output div:last").addClass("triange");
Output : div.shape.circle.red.triange

Input : $("#output div:last").addClass("triange").addClass("orange");
Output : div.shape.circle.red.triange.orange

Input : $("#output div:last").show().addClass("triange").addClass("orange");
Output : div.shape.circle.red.triange.orange

Input : $("#output div:last").addClass("triange").addClass("orange").show();
Output : div.shape.circle.red.triange.orange
