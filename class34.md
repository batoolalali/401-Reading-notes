# Authentication + Role Based Authorization

## <Auth /> component

Based on your permissions and login status, it either gives you access to a component or jsx or hides it.
Must not use Redux, We don’t want to force implementors into a specific state management system.

- Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

- BENEFITS OF RBAC
1. Managing and auditing network access is essential to information security. 
2. Access can and should be granted on a need-to-know basis. 
3. With hundreds or thousands of employees, security is more easily maintained by limiting unnecessary access to sensitive information based on each user’s established role within the organization. 