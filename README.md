# Quiz1_887342
# Hello World Program in Ruby
#puts "Hello World!";
US_states = 

	{"Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}
	
	
	US_states.each do | key, value|
	    if value[-1] =="T"||value[-1] =="N"
  puts  value
  
  end
  
  end
   puts "-------------------------------------------->"
  #----------------------------2------------------------------
  puts US_states.sort.reverse
  
  #----------------------------3--------
  puts "-------------------------------------------->"
  US_states.each do | key, value|
	if (key[0] == "A"|| key[0] =="E"|| key[0] =="I"|| key[0] =="O"|| key[0] =="U") &&  
	    (key[key.length-1] == "a"||key[key.length-1] =="e"||key[key.length-1] =="i"||key[key.length-1] =="o"||key[key.length-1] =="u" )  
  puts  key
  
    
  end
  
  
  end
  
	#US_states.each{"Vermont" puts "VT"     }
	
	#def convert1 (line)
   # if line != nil
    #line.gsub!(Re_amp,  Amp)
    #line.gsub!(Re_apos, Apos)
    #line.gsub!(Re_quot, Quot)
    #line.gsub!(Re_lt, Lt)
    #line.gsub!(Re_gt, Gt)
    #return line
    #else
    #return line
    #end
    #end

#ข้อสองผมยังไม่ได้ทำเพราะไม่ทันครับ555+
