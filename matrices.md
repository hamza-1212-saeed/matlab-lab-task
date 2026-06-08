# matlab-lab-task
final exam of engineering workshop
a=magic(6);
z=[1;-2;-3;-4;-5;-6];
ans =

    35     1     6    26    19    24
     3    32     7    21    23    25
    31     9     2    22    27    20
     8    28    33    17    10    15
    30     5    34    12    14    16
     4    36    29    13    18    11

>> ans(:,1)=[1;-2;-3;-4;-5;-6]

ans =

     1     1     6    26    19    24
    -2    32     7    21    23    25
    -3     9     2    22    27    20
    -4    28    33    17    10    15
    -5     5    34    12    14    16
    -6    36    29    13    18    11

>> untitled
>> z=[1;-2;-3;-4;-5;-6];
>> x=ans\z

x =

     1
     0
     0
     0
     0
     0

>> det(ans)

ans =

   5.1788e+06
**PLOT TASK**:
t=0.5*pi+3.6;
y1=e^(-t);
y2=sin(t);
y3=e^(-t)*sin(t);

subplot(1,1,1);
plot(t,y1,'g');
title("e^.(-t)");
xlabel("time");
ylabel("amplitude");
grid on;

subplot(1,1,2);
plot(t,y2,'k');
title("sin(t)");
xlabel("time");
ylabel("amplitude");
grid on;

subplot(1,1,3);
plot(t,y3,'r');
title("e^.(-t).*sin(t)");
xlabel("time");
ylabel("amplitude");
grid on;


t=0.5*pi+3.6;
y1=e^(-0.5*t);
y2=cos(2*t);
y3=e^(-0.5*t)*cos(2*t);

subplot(1,1,1);
plot(t,y1,'g');
title("e^.(-t)");
xlabel("time");
ylabel("amplitude");
grid on;

subplot(1,1,2);
plot(t,y2,'k');
title("sin(t)");
xlabel("time");
ylabel("amplitude");
grid on;

subplot(1,1,3);
plot(t,y3,'r');
title("e^.(-t).*sin(t)");
xlabel("time");
ylabel("amplitude");
grid on;
