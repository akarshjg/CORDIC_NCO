module phase_accumalator

(
input clk, reset, step,
output q, theta,
)


always@(posedge clk)
begin

step <= 14’d785;

if (reset == 1)
begin
theta<=0;
end

else
begin
theta <= theta+step;
end


end
