# programacion_5.11
%numeral 5.11--
clf
clear all
z=0:2*pi;
s=sin(z);
r=cos(z);
plot(z,s,'g')
hold on
plot(z,r,'r')

grid on
axis([0 6 -1 1])
title('nimeral 5.11')
legend('seno','cos')
