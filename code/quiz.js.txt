setScreen("screen_Welcome");
onEvent("button_Continue", "click", function( ) {
  setScreen("screen1");
});
onEvent("checkbox_Annabelle", "click", function( ) {
  setText("label6", "Wrong");
});
onEvent("checkbox_The_Nun", "click", function( ) {
  setText("label6", "Correct");
});
onEvent("button1", "click", function( ) {
  setText("label6", "");
  setScreen("screen2");
});
onEvent("checkbox_Easter_bunny", "click", function( ) {
  setText("label9", "Wrong");
});
onEvent("checkbox_Hop", "click", function( ) {
  setText("label9", "Correct");
});
onEvent("button3", "click", function( ) {
  setText("label9", "");
  setScreen("screen3");
});
onEvent("checkbox_life_of_Pi", "click", function( ) {
  setText("label7", "Wrong");
});
onEvent("checkbox_Titanic", "click", function( ) {
  setText("label7", "Correct");
  setScreen("screen3");
});
onEvent("button2", "click", function( ) {
  setText("label7", "");
  setScreen("screen5");
});
onEvent("checkbox_Journey_2", "click", function( ) {
  setText("label13", "Wrong");
});
onEvent("checkbox1", "click", function( ) {
  setText("label13", "Correct");
});
onEvent("button4", "click", function( ) {
  setText("label13", "");
  setScreen("screen6");
});
onEvent("checkbox3", "click", function( ) {
  setText("label17", "Wrong");
});
onEvent("checkbox4", "click", function( ) {
  setText("label7", "Correct");
});
onEvent("button5", "click", function( ) {
  setScreen("screen7");
});
