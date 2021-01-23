# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.

You have been called on to demonstrate your newly learned skills to create a full stack drink menu application. The application must:

1) Display graphics representing the ratios of ingredients in each drink.
2) Allow public users to view drink names and graphics.
3) Allow the shop baristas to see the recipe information.
4) Allow the shop managers to create new drinks and edit existing drinks.

## Tasks

There are `@TODO` comments throughout the project. We recommend tackling the sections in order. Start by reading the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

We started the full stack application for you. It is desiged with some key functional areas:

### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app. 

[View the README.md within ./frontend for more details.](./frontend/README.md)


## Dummy account to test

### Barista account

```
User: barista@example.com
password: test_user_2020
```
```
Token (which can be expired at - "2021-01-23 / 22:54:25 / GMT-03000"):
```
`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IlVudTVmRzc2NHRYM2RTeTBfU3A1UCJ9.eyJpc3MiOiJodHRwczovL2Rldi1mc25kLTIwMjEudXMuYXV0aDAuY29tLyIsInN1YiI6ImF1dGgwfDYwMDY1MDFhYjEzZTU3MDA3Njg2ZmI3MiIsImF1ZCI6ImNvZmZlZXNob3AiLCJpYXQiOjE2MTEzNjY4NjUsImV4cCI6MTYxMTQ1MzI2NSwiYXpwIjoidU5wa2JaOTJTaWhPU2VVc0FubnNudkt6M2RDOGtZUmMiLCJzY29wZSI6IiIsInBlcm1pc3Npb25zIjpbImdldDpkcmlua3MtZGV0YWlsIl19.AFcHFkESMIf6MZ3IQQdNUfyxxRM2rucOz5DXP7SWEx3z1HPXqusFUiDh99qmsh-aTSz2--nBv5zZdgjr5OgY0_dn6gyM2gHou77lkoONxp8bFJx-EhubsSNnMMnGeNHWog8ilJR1lSXz0rcIjZhcJ49FkNtfaXkZxAyV4lolPfMHU30u-w88CDFSNWmkWo4L9zBX_QV9N_cOMHwRXcLmxZIipYXKGfhS3Yy4PeFp7MEqBO3PSnWhnB-qGg3q4XN0MS9MajLnokoVI_cx_DDjavuJkqHS13VBC7quXJRAoeZF2XoJha2Ne-_HmzMdhXFhCmrCZO5MHwD6OAqDI_Nxog`


### Manager account

```
User: manager@example.com
password: test_manager_2020
```
```
Token (which can be expired at - "2021-01-23 / 23:12:57 / GMT-03000"):
```
`eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IlVudTVmRzc2NHRYM2RTeTBfU3A1UCJ9.eyJpc3MiOiJodHRwczovL2Rldi1mc25kLTIwMjEudXMuYXV0aDAuY29tLyIsInN1YiI6ImF1dGgwfDYwMDY0ZjNkMTUyMjE4MDA2YTNjYzEwMCIsImF1ZCI6ImNvZmZlZXNob3AiLCJpYXQiOjE2MTEzNjc5NzcsImV4cCI6MTYxMTQ1NDM3NywiYXpwIjoidU5wa2JaOTJTaWhPU2VVc0FubnNudkt6M2RDOGtZUmMiLCJzY29wZSI6IiIsInBlcm1pc3Npb25zIjpbImRlbGV0ZTpkcmlua3MiLCJnZXQ6ZHJpbmtzLWRldGFpbCIsInBhdGNoOmRyaW5rcyIsInBvc3Q6ZHJpbmtzIl19.ezuu0FNli24k8xC6h1qedovLCDtWceVx0C9FVNnJzuT5sEhllELP9w3lwF2pfsAXpu6XeoGOMPoUXPGI7HoJmQOCFfK269Uurzx_0iHJi7kFnHDbwaybkCstp4BXmnE0ZkOpfFsrm5ay_1a-HhihRdx5zpCRtB-NiwXS91elhCqlanDmoXm2sJ6mrRCR7qfXGNIUxrtjAelpqpunoKH5D_xGIbPr-TtCBDEPEITLcNxiGTO-i9Me7ZTVe_fn9haa-2gHaulGS8MlAvaf5ALQDxIT4fVCI_q_WOLJ1hHRbzAqLKpFsqfIqDSlAM94XjhZv2kG2FjfZePpyEu4In32Ng`
