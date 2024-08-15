<h1>AWS EKS Fargate Profile</h1>
<h2>Technologies used</h2>

- <b>Kubernetes</b> 
- <b>AWS EKS</b>
- <b>AWS Fargate</b>




<h2>Detailed Description of Project </h2>
1. Create Fargate IAM Role<br/>
2. Create Fargate profile<br/>
3. Deploy an example application to EKS cluster using Fargate profile<br/>






   <p align="">
   <h2>step 1    Create Fargate IAM Role</h2>
   From AWS IAM service, Create IAM role for EKS fargate pod<br/>
   Attach  'AmazonEKSFargatePodExecutionRolePolicy'<br/>
  
   <img src='./pi/p2.png' height="80%" width="80%" alt="Disk Sanitization Steps">

 


   <h2>step 2  Create Fargate Profile</h2>
   Create a fargate profile from the cluster compute <br/>
   Deploy an example application to EKS cluster using Fargate profile<br/>
  
  <img src='./pi/p3.png' height="80%" width="80%" alt="Disk Sanitization Step"> 


  Configuration of fargate rules<br/>
  Selectors are required to indicate pod needed to be scheduled by fargate<br/>
  <img src='./pi/p5.png' height="80%" width="80%" alt="Disk Sanitization Step"> 


  Fargate profile is created and active<br/>
  <img src='./pi/p8.png' height="80%" width="80%" alt="Disk Sanitization Step"> 
  
  
  
  Selectors created must be added to the pod configuration file<br/>
  <img src='./pi/p6.png' height="80%" width="80%" alt="Disk Sanitization Step"> 


  The deployment and service are created in the the cluster<br/>
  AwS configures fargate and run application on it<br/>
  <img src='./pi/p7.png' height="80%" width="80%" alt="Disk Sanitization Step"> 
  
  

  


   
     

</p>
