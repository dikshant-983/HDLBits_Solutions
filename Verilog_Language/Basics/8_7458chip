module top_module ( 
    input p1a, p1b, p1c, p1d, p1e, p1f,
    output p1y,
    input p2a, p2b, p2c, p2d,
    output p2y );
    
    wire x , w , y ,z ;
    assign x = p1a&&p1b&&p1c;
    assign w = p1d&&p1e&&p1f;
    assign y = p2a&&p2b;
    assign z = p2c&&p2d;
    assign p1y = x || w;
    assign p2y = y || z;
    


endmodule
