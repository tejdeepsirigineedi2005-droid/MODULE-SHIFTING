# MODULE-SHIFTING
module top_module ( input clk, input d, output q );
wire w2;
    wire w3;
    

    my_dff dff1(.clk(clk), .d(d), .q(w2));
    my_dff dff2(.clk(clk), .d(w2), .q(w3));
    my_dff dff3(.clk(clk), .d(w3), .q(q));
    
endmodule
<img width="1366" height="768" alt="Screenshot 2026-06-18 132235" src="https://github.com/user-attachments/assets/24904f6f-3ba3-4ef8-9692-73efb18c7ad1" />
