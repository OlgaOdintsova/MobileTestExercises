# MobileTestExercises HW2

## 1. For existing native mobile autotest try to use another locator (xpath, classname, ?). Define these locators using Appium Inspector. Are there any difference with id version?
All this ways to get locator are similar to each other, but the AccessibilityId name is the shortest.

## 2. Modify existing tests to run on a real device. What should be changed?
The deviceName capability in driver setup file should be changed.

## 3. Connect a real device to Appium (describe required actions) and run tests. Are there any difference with run on emulator?
In theory, I know what have to open Appium Start Inspector Session On the Automatic Server tab or create a new Capability Set for device (Android, device name, path to the application).
In reality, I do not have a working Android device

## 4. What should be improved/changed in existing test code? Why, for what?
Hardcoded values, Thread.sleep, Absolute paths. Name of the test should have sense and tell what feature is tested. Capabilities should be moved to property file.
The structure of the project is far from ideal. No descriptions of all (class, metod). We don't test something.
