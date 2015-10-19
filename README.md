# Punto.-Q.5.45
Further Analysis
Q.5.45 Load and run the script fi le, ez_xsinx of Example 5.8.
% Script file: ez _ xsinx

figure(1)

ezplot(‘sin(1/x)’)

hold on

ezplot(‘x*sin(x)’)

disp(‘*********************************************’)

disp(‘The solutions outside -0.15≤ x ≤0.15 are :’)

ginput

disp(‘*********************************************’)

figure(2)

ezplot(‘sin(1/x)’)

hold on

ezplot(‘x*sin(x)’)

axis([-0.5 0.5 -2 2])
