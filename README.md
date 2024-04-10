# Assignment-3
# App Intro

Let’s start with the intro about the application. So, Feel-Fit is a fitness + diet management application in which user can maintain their diet plan with to the point calorie tracking for every bite they take, and not only that you can monitor your BMI as your height or weight increases or decreases, other that that you can read about the basic regular exercises that anyone can do even in there home with all the comfort.

## App Flow

1. **Splash Screen**: 
    - Just a simple Splash Screen which is having app logo and name.

2. **Login Screen**: 
    - If the user has an account, then they can login directly to the home page after credential verification and at the same time we will fetch the user’s data from the backend (Firebase).
    - If user is already logged in so for that condition, we are checking the user auth details at the runtime only and making sure a seamless rendering to the home screen.
    - If the user is new so they can visit the register screen, we will talk about it in the next point.

3. **Register Screen**: 
    - This screen comes into the picture only when the user is a new user in that case they can go to register screen, and after entering some basic info (email, password) to create a new account and then they will be redirected to the home screen.

4. **Home Screen**: 
    - On this screen the very first thing that user will see is greeting of the day (depending upon the users time zone and current time), after that the home screen is having so many components in itself so lets break them for better understanding:
        - **Carousal**: When it comes to fitness motivation is the thing which keeps you moving forward and for that motivation, we are having this carousal with different pictures to keep you motivated throughout.
        - **Dynamic progress bar**: This helps you track and check your calory intake as if you have reached your calory goal or not. And there is more to it when you click anywhere on the card you will find detailed breakdown of your diet (calorie, protein, fat and carbs). And there is one more thing about this card there is one circular plus icon it is something we will discuss in some other point.
        - **Height and Weight card**: This card is also a dynamic card which holds the height and weight entered by the user and if you click on the card, you will be able to update your vitals anytime.
        - **BMI Card**: Just next to the height & which shows your exact BMI as per your height and weight and when you click on the card you can see your BMI with more details about the same.
        - **Exercise Card**: This card is also a dynamic card which holds 3 types of exercises (Exercises for Muscle Gain, Weight Loss and just warm up exercises) and you can find them out after clicking on the card.
        - **Motivational Text**: At the bottom of the screen, you will find a dynamic text which will change by itself whenever you will start the application.
        - **Profile Icon**: When you click on the icon you will be redirected to a new screen Where you can set you username and also set you calorie target that you want to achieve and these details will be rendered on the home screen. And other than that logout button is also on this screen only.

## Circular Plus Icon on the Calorie Tracker Card

- So, when you will click on the icon you will be redirected to a new screen on which you will find the list of all the items you have had and just at the bottom of the screen you will find another circular plus button to add new food item when you click on that you will again get redirected to a new screen where you have to fill all the food related details that you ate. And after adding the details you will be redirected to the screen where we are having the list of food items.
- Now let’s discuss how the calories are going to get calculated when you click on any of the listed items you have to fill one more detail that is amount of that particular food that you ate. And then the system will automatically calculate everything on its own.

