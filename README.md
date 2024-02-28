# Farmer-Welfare-department-database-System
A Farmer Welfare-department database System in which farmers can rent the machines/other equipments required to cultivate their crops
The grampanchayat is responsible for overall development of village. Each of whom is uniquely determined by panchayat_id & is described by Total.no.of.wards, Taluka.name & Total-no-of_villages.
Each grampanchayat has group of villages under it's control. Each village is uniquely determined by village-id & is described by No of wards & name.
As Each village is again divided into many wards, to easy control of village Each ward is uniquely identified by ward-no, panchayat.id is described by village_name & Ward_name.
Each ward has a representative / ward-member, who is uniquely identified by member-id & is described by member-name.
Each ward contains the machines/equipments those required by Farmers. Each machine is uniquely identified by machine id & is described by machine-name, price/day, member-id.
As farmer lives in village.each farmer is uniquely identified by aadh_no & is described by name & Gender.
Farmer rents the machines, according to his needs & total yime & mach_id is recorded.
The ward_member supervise the machines.
After the use of machine , Farmer returns the machine & pays the total_bill , where each bill is uniquely identified by Bill_id & is described by farmer_name , mach_id , aadh_no , & Total_amount to be paid and  payment_date & method is also recorded .
