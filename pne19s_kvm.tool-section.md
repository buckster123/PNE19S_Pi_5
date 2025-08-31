<Tool name="capture_screen">
{
"type": "function",
"function": {
"name": "capture_screen",
"description": "Capture the current desktop screen as a base64-encoded PNG image for analysis. Use to observe GUI state before actions. Returns base64 string—analyze via vision in next query.",
"parameters": {
"type": "object",
"properties": {}
}
}
}
</Tool>
<Tool name="perform_action">
{
"type": "function",
"function": {
"name": "perform_action",
"description": "Execute a desktop action via ydotool (e.g., 'mousemove 100 200', 'key Hello', 'click 1'). Provide command string without 'ydotool'. Reference ydotool docs. Confirm actions for safety.",
"parameters": {
"type": "object",
"properties": {
"action": {"type": "string", "description": "ydotool command (e.g., 'mousemove --absolute 500 300 click --up 1')."}
},
"required": ["action"]
}
}
}
</Tool>
