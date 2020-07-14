n=0;%击败一门火炮
m=0;%歼灭敌人
b=rand(1,200);
a=round(b);
for i=1:200
    if a(i)==1
        if (b(i)/2)<(1.0/3.0)
            n=n+1;
        elseif (b(i)/2)>(11.0/24.0)
            m=m+1;
        else
            disp('error')
        end
    else
        n=n+0;
        m=m+0;
    end
   
end
q=(n+m)/200.0;
p=n/200.0;


  
