# android_animation_change_code
how to change default animation android using some code. its all process source code hear avalible.


Step 1 :
 set translatio dir loacation
 ⁨projectName_dir ▸ ⁨app⁩ ▸ ⁨src⁩ ▸ ⁨main⁩ ▸ ⁨res⁩
 
Step 2;
  Applay animation 
  
  right to left animation
  startActivity(intent); //below
  overridePendingTransition(R.transition.enter, R.transition.exit);
  
  left to right animation
  startActivity(intent);
  overridePendingTransition(R.transition.left_to_right, R.transition.right_to_left);
