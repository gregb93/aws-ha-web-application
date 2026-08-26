# aws-ha-web-application
Designed and deployed a highly available web application architecture on AWS using multiple Availability Zones.
                  Internet
                     │
                     ▼
                Route 53
                     │
                     ▼
          Application Load Balancer
                 /        \
                /          \
               ▼            ▼
          EC2 Instance  EC2 Instance
             AZ-1           AZ-2
                \            /
                 \          /
                  ▼        ▼
                    RDS
                 Database
