<template>
  <p class="text-left">Job post</p>
  <v-table fixed-header
  height="680px"
  >
      <thead>   
          <tr>
              <th>
                  Name
              </th>
              <th >
                  Title
              </th>
              <th>
                  Company
              </th>
              <th>
                  Location
              </th>
              <th>
                  Description
              </th>
              <th>
                  Requirements
              </th>
              <th>
                  Salary
              </th>
          </tr>
      </thead>
      <tbody>
          <tr v-for="item in jobPosts" :key="item.title">
              <td>{{ item.name }}</td>
              <td>{{ item.title}}</td>
              <td>{{ item.company}}</td>
              <td>{{ item.location}}</td>
              <td>{{ item.description}}</td>
              <td> {{ item.requirements }}</td> 
              <td>{{ item.salary}}</td>
          </tr>
      </tbody>
  </v-table>
  </template>
  
    
  <script>
  export default {
      name: 'JsonTable',
      data() {
          return {
              "jobPosts": [{
                      "name":"Vijay",
                      "title": "Full stack developer",
                      "company": "XYZ",
                      "location": "Newham",
                      "description": "We are seeking a highly skilled Full stack developer to join our team and help develop new products and features.",
                      "requirements":"Bachelor's degree in CSE or related field, 3+ years of experience in Full stack developer",
                      "salary": "$120,000 - $140,000"
                  },
                  {
                      "name":"Surya",
                      "title": ".NET developer",
                      "company": "ABC",
                      "location": "San Francisco",
                      "description": "We are seeking a highly skilled .NET developer to join our team and help develop new products and features.",
                      "requirements":"Bachelor's degree in Computer science or related field, 2+ years of experience in Full stack developer",
                      "salary": "$130,000 - $150,000"
                  },
                  {
                      "name":"Vicky",
                      "title":"Full stack developer",
                      "company": "Connect Out Solutions",
                      "location": "london",
                      "description": "We are seeking a highly skilled Full stack developer to join our team and help develop new products and features.",
                      "requirements":"Bachelor's degree in Accounting or related field, 1+ years of experience in Full stack developer " , 
                      "salary": "$70,000 - $90,000"                    
                  },
                  {
                      "name":"Guru",
                      "title": "Team leader",
                      "company": "Connect Out Solutions",
                      "location": "India,Trichy.",
                      "description": "We are seeking a highly skilled Team leader to join our team and help develop new products and features",
                      "requirements": "Bachelor's degree in Accounting or related field, 5+ years of experience in Team leader ",
                      "salary": "$120,000 - $190,000"
                  },
                  {
                      "name":"Jehoash",
                      "title": "HR officer",
                      "company": "Connect Out Solutions",
                      "location": "India,Chennai.",
                      "description": "We are seeking an experienced HR officer to join our team and assist with HR reporting, budgeting, and tax compliance.",
                      "requirements": "Bachelor's degree in Accounting or related field, 8+ years of experience in HR officer",
                      "salary": "$100,000 - $140,000"
                  },
                  {
                      "name":"Anu",
                      "title": "Project manager",
                      "company": "Connect Out Solutions",
                      "location": "India ,Trichy.",
                      "description": "We are seeking an experienced Project manager to join our team and assist with HR reporting, budgeting, and tax compliance.",
                      "requirements":  "Bachelor's degree in Accounting or related field, 3+ years of experience in Project manager",
                      "salary": "$100,000 - $190,000"
                  },
                  {
                      "name":"Ram",
                      "title": "HR officer",
                      "company": "Connect Out Solutions",
                      "location": "India ,Trichy.",
                      "description": "We are seeking an experienced Project manager to join our team and assist with HR reporting, budgeting, and tax compliance.",
                      "requirements":  "Bachelor's degree in Accounting or related field, 2+ years of experience in Project manager",
                      "salary": "$100,000 - $190,000"
                  },
                  {
                      "name":"Jinna",
                      "title": "Program manager",
                      "company": "Connect Out Solutions",
                      "location": "India",
                      "description": "We are seeking an experienced Project manager to join our team and assist with HR reporting, budgeting, and tax compliance.",
                      "requirements":  "Bachelor's degree in Accounting or related field, 8+ years of experience in Project manager",
                      "salary": "$100,000 - $190,000"
                  },
                  {
                      "name":"surabai",
                      "title": "Project manager",
                      "company": "Connect Out Solutions",
                      "location": "Dubai",
                      "description": "We are seeking an experienced Project manager to join our team and assist with HR reporting, budgeting, and tax compliance.",
                      "requirements":  "Bachelor's degree in Accounting or related field, 1+ years of experience in Project manager",
                      "salary": "$100,000 - $190,000"
                  },
                  {
                      "name":"Bharath",
                      "title": "Full stack developer",
                      "company": "Connect Out Solutions",
                      "location": "India ,Trichy.",
                      "description": "We are seeking an experienced Project manager to join our team and assist with Full stack developer , budgeting, and tax compliance.",
                      "requirements":  "Bachelor's degree in Accounting or related field, 3+ years of experience in Project manager",
                      "salary": "$100,000 - $190,000"
                  },
                  {
                      "name":"Anand",
                      "title": "Project manager",
                      "company": "Connect Out Solutions",
                      "location": "India ,Trichy.",
                      "description": "We are seeking an experienced Project manager to join our team and assist with HR reporting, budgeting, and tax compliance.",
                      "requirements":  "Bachelor's degree in Accounting or related field, 7+ years of experience in Project manager",
                      "salary": "$100,000 - $190,000"
                  },
                  {
                      "name":"Hari",
                      "title": "HR officer",
                      "company": "Connect Out Solutions",
                      "location": "India ,Trichy.",
                      "description": "We are seeking an experienced Project manager to join our team and assist with HR reporting, budgeting, and tax compliance.",
                      "requirements":  "Bachelor's degree in Accounting or related field, 4+ years of experience in Project manager",
                      "salary": "$100,000 - $190,000"
                  },
              ]
          }
      }
  }
  </script>