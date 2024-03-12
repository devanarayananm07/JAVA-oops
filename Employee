import java.util.*;
class Employee
{
    int eNo,eSalary;
    String eName;
    Employee(String a,int b,int c)
    {
        eName=a;
        eNo=b;
        eSalary=c;
    }
    int return_id()
    {
        return eNo;
    }
}
class company
{
    public static void main(String args[])
    {
        Scanner s=new Scanner(System.in);
        Employee E[]=new Employee[5];
        int n,id,salary;
        String name1;
        System.out.println("Enter no.of Employees");
        n=s.nextInt();
        s.nextLine();
        for(int i=0;i<n;i++)
        {
            System.out.println("Enter the employee details");
            System.out.println("Enter the employee id");
            id=s.nextInt();
            s.nextLine();
            System.out.println("Enter the employee Name");
            name1=s.nextLine();
            System.out.println("Enter the employee Salary");
            salary=s.nextInt();
            s.nextLine();

            E[i]=new Employee(name1,id,salary);
        }
        System.out.println("Enter id of employee to be searched");
        int ele=s.nextInt();
        int h,f=0;
        for(int i=0;i<n;i++)
        {
            h=E[i].return_id();
            if (ele==h)
            {
                f=f+1;
            }
        }
        if(f>0)
        {
            System.out.println("The Employee having the id" + ele + "is presented");
        }
        else
        {
            System.out.println("The Employee having the id" + ele + "is not presented");
        }

    }
}
