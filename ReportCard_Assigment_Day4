pragma solidity ^0.4.17 < 0.6.12; 

contract ReportCard {
    
    string public name;
    uint public rollNo;
    string public batch;
    uint public maths;
    uint public science;
    uint public english;
    uint public socialScience;
    string public status;
    
    
    function Report_Card(string newName, uint newRollName, string newBatch, uint newMaths, uint newScience, uint newEnglish, uint newSocialScience) public {
        name = newName;
        rollNo =  newRollName;
        batch =  newBatch;
        
        //Enter Marks Out of 50
        maths = newMaths;
        science = newScience;
        socialScience = newSocialScience;
        english = newEnglish;
        
        uint result = maths + english+science+socialScience;
        
        if(result < 100){
            status = "Fail";
        }else{
            status = "Pass";
        }
        
    } 

    
    function getReportCard() public view returns(string,uint,string,uint,uint,uint,uint,string){
        return (name,rollNo,batch,maths,science,english,socialScience,status);
    }
}
