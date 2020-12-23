# tips

rosrun xacro xacro.py pan_tilt.xacro > pan_tilt_generated.urdf

roslaunch urdf_tutorial display.launch model:='$(find urdf_tutorial)/urdf/01-myfirst.urdf'

rosrun collada_urdf urdf_to_collada "MY_ROBOT".urdf "MY_ROBOT".dae

you can render the kuri model using the guide as above.


from selenium import webdriver
import time
driver = webdriver.Firefox()
driver.get('file:///home/kjh948/workspace/hobby/tablet-robot-face/index.html')
#driver.maximize_window()
#driver.fullscreen_window()

print("cmd7")
driver.find_element_by_xpath('/html/body/div[1]/button[7]').click()
time.sleep(1)
print("cmd6")
driver.find_element_by_xpath('/html/body/div[1]/button[6]').click()

time.sleep(1)
print("cmd5")
driver.find_element_by_xpath('/html/body/div[1]/button[5]').click()

