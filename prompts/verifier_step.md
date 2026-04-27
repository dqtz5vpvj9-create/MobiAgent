<image_before> <image_after>

Target step: "{current_step_desc}"

Compare the two screenshots:
- Image 1 (before): The state when this step started
- Image 2 (after): The current state after action(s) were taken

Determine if the target step has been completed by checking if the expected UI change has occurred.

Output ONLY a JSON object:
{{"completed": true}} if the target step is done
{{"completed": false}} if the target step is NOT done yet
