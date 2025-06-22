CloudTasker is a cloud-native CRUD application that allows you to manage employee records seamlessly using Spring Boot, Amazon RDS, and GitHub. Designed with DevOps in mind, it showcases real-world AWS resource handling, CI/CD readiness, and deployment flexibility.

📌 Tech Stack & Tools
| Category | Tool/Tech | 
| Backend Framework | Spring Boot (Java) | 
| Database | Amazon RDS (MySQL/Aurora) | 
| Cloud Provider | AWS (VPC, Security Groups, IAM) | 
| Infrastructure | Terraform (optional for provisioning) | 
| API Testing | Postman | 
| IDE & Dev Tools | IntelliJ IDEA, Sqlectron | 
| Version Control | Git + GitHub | 

📌 Features
- Add, update, delete, and list employee records via RESTful API
- Connected to a MySQL-compatible Aurora DB hosted on AWS RDS
- IAM-managed permissions & secure AWS infrastructure setup
- Structured package layout with Service, Repository, and Controller layers

📌 Endpoints Preview
| Method | Endpoint | Description | 
| GET | /employees | Get all employees | 
| GET | /employees/{id} | Get employee by ID | 
| POST | /employees | Add new employee | 
| PUT | /employees/{id} | Update employee | 
| DELETE | /employees/{id} | Delete employee | 

📌 Setup Instructions
# Clone the repository
git clone https://github.com/Dhineia/cloudtasker-employee-system.git

# Open in IntelliJ and run
./mvnw spring-boot:run

💡 Lessons Learned
- Navigated IAM permissions and AWS billing traps
- Debugged stubborn VPC and NAT Gateway deletions
