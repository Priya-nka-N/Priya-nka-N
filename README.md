class Hospital

{

//Instance variable

String patientName;

int patientid;

//Static(class) variable

static String DocName="Dr. Murthy";

void sethospital(String pN ,int pld)

{

patientName=pN; patientid=pld;

}

String getpatientName()

{

return patientName;

}

int getpatientid()

{

return patientid;

}

}

public class DemoScopeofVariables

{

public static void main(String args[])

{

//Local variable

String hospitalName="Apollo Hospital";

Hospital patient1=new Hospital();

patient1.sethospital("Anita Joseph",101);

System.out.println("The patient" +patient1.getpatientName()+" With the Id"

jkqefgiiwrl;wr;hwhi;+patient1.getpatientid()+" is treated by" +patient1.DocName+"at"

+hospitalName);

}

}

<!---
Priya-nka-N/Priya-nka-N is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
