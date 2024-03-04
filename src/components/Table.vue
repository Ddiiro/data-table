<template>
  <div>
    <table>
        <tr>
            <th>
                Full Name
            </th>
            <th>
                Gender
            </th>
            <th>
                Occupation
            </th>
            <th>
                Employment status
            </th>
        </tr>
        
        <tr 
            v-for="employee in tableData"
            :key="employee.pk"
        >
            <td>{{ employee.fullName }}</td>
            <td>{{ employee.gender }}</td>
            <td>{{ employee.occupation }}</td>
            <td>{{ employee.status }}</td>
        </tr>
    </table>
  </div>
</template>
<script>
    export default {
                components: {
              
                },
                
                data() {
                    return { 
                        tableData: [
                        { 
                            pk: 1, 
                            fullName: "John Doe", 
                            gender: "Male", 
                            occupation: "Software Engineer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 2, 
                            fullName: "Jane Smith", 
                            gender: "Female", 
                            occupation: "Data Scientist", 
                            status: "Employed" 
                        },
                        { 
                            pk: 3, 
                            fullName: "Michael Johnson", 
                            gender: "Male", 
                            occupation: "Project Manager", 
                            status: "Employed" 
                        },
                        { 
                            pk: 4, 
                            fullName: "Emily Brown", 
                            gender: "Female", 
                            occupation: "UX Designer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 5, 
                            fullName: "Christopher Lee", 
                            gender: "Male", 
                            occupation: "DevOps Engineer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 6, 
                            fullName: "Jessica Taylor", 
                            gender: "Female", 
                            occupation: "Frontend Developer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 7, 
                            fullName: "Daniel Wilson", 
                            gender: "Male", 
                            occupation: "Database Administrator", 
                            status: "Employed" 
                        },
                        { 
                            pk: 8, 
                            fullName: "Sarah Martinez", 
                            gender: "Female", 
                            occupation: "Software Engineer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 9, 
                            fullName: "Matthew Anderson", 
                            gender: "Male", 
                            occupation: "Data Analyst", 
                            status: "Employed" 
                        },
                        { 
                            pk: 10, 
                            fullName: "Amanda Harris", 
                            gender: "Female", 
                            occupation: "Product Manager", 
                            status: "Employed" 
                        },
                        { 
                            pk: 11, 
                            fullName: "James Thompson", 
                            gender: "Male", 
                            occupation: "Backend Developer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 12, 
                            fullName: "Jennifer Clark", 
                            gender: "Female", 
                            occupation: "UI Designer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 13, 
                            fullName: "David Rodriguez", 
                            gender: "Male", 
                            occupation: "Network Engineer", 
                            status: "Employed" 
                        },
                        { 
                            pk: 14, 
                            fullName: "Ashley Baker", 
                            gender: "Female", 
                            occupation: "System Administrator", 
                            status: "Employed" 
                        },
                        { 
                            pk: 15, 
                            fullName: "Robert Young", 
                            gender: "Male", 
                            occupation: "Security Analyst", 
                            status: "Unemployed" 
                        },
                ]
            };
        },
        props: {
        },
        computed: {
        },
        methods: {
        },
    };
</script>

<style>
    table {
        font-size: 20px;
        border: 2px solid black;
        width: 90%;
        margin: 20dvh auto;
        padding: 10px;

    }

    th {
        border: 1px solid #000;
        padding-left: 0;
        margin-left: 0;
    }

    td {
        border: 1px solid #000;
    }
</style>