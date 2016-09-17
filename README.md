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
	
US_states.each{|x,y| puts y if y[y.length-1] =="T"|| y[y.length-1] =="N" }


 
puts " 




*************************************** More to Less ***************************************




"

US_states_R = Hash[US_states.to_a.reverse]

US_states_R.each{|x,y|  puts"#{x} => #{y}" }


puts " 




*************************************** AEIOU ***************************************




"
US_states.each{|x,y| puts x if (x[0] =="a"|| x[0] =="A" || x[0] =="e"|| x[0] =="E" || x[0] =="i"|| x[0] =="I" || x[0] =="o" || x[0] =="O" || x[0] =="u" || x[0] =="U") && (x[x.length-1] =="a"|| x[x.length-1] =="A" || x[x.length-1] =="e"|| x[x.length-1] =="E" || x[x.length-1] =="i"|| x[x.length-1] =="I" || x[x.length-1] =="o" || x[x.length-1] =="O" || x[x.length-1] =="u" || x[x.length-1] =="U") }



ข้อที่ 2. ยังทำไม่ได้ครับอาจารย์เนื่องจากยังขาดการทบทวนที่ดี  ขอบคุณมากๆครับ
	
