# MediConnect
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
![MIT](https://img.shields.io/github/license/nisarg-vaghela/MediConnect?color=blue)


MediConnect is a website that connects doctors, patients, and ambulance providers. Patients can select a date and doctor to consult, and the system will automatically generate an appointment time based on the doctor's schedule. Patients can also view their current and past appointments and book ambulance services. Doctors can accept or reject appointments, view all their current and past appointments, and upload detailed prescriptions for patients.

## Visit Online

This website is hosted at [https://MediConnect.onrender.com/](https://MediConnect.onrender.com/)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Your machine should have Npm(or Yarn), Node.js, and MongoDB installed to use it locally.

## Setup and Installation

### Setting up the repository locally

1. First fork the repo :fork_and_knife: to your account.  
   Go to the forked repo and clone it :busts_in_silhouette: to your local machine:

```sh
git clone https://github.com/Your_Username/MediConnect.git
```

This will make a copy of the code to your local machine.

2. Now move to the `MediConnect` directory.

```sh
cd MediConnect
```

3. Now check the remote of your local code by:

```sh
git remote -v
```

The response should look like:

```sh
origin	https://github.com/Your_Username/MediConnect.git (fetch)
origin	https://github.com/Your_Username/MediConnect.git (push)
```
To add upstream to remote, run:

```sh
git remote add upstream https://github.com/nisarg-vaghela/MediConnect.git
```

Again run `git remote -v`, the response should look like:

```sh
origin	https://github.com/Your_Username/MediConnect.git (fetch)
origin	https://github.com/Your_Username/MediConnect.git (push)
upstream	https://github.com/nisarg-vaghela/MediConnect (fetch)
upstream	https://github.com/nisarg-vaghela/MediConnect (push)
```

4. Once the remote is set, install all the necessary dependencies by the following command:

```sh
npm install
```
### Run locally

Run the below command to start the server:

```sh
npm run dev
```
Go to: [http://localhost:4000](http://localhost:4000)

### Contributing

We really like contributions in several forms, see [CONTRIBUTING.md](https://github.com/nisarg-vaghela/MediConnect/blob/master/docs/CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](https://github.com/nisarg-vaghela/MediConnect/blob/master/docs/CODE_OF_CONDUCT.md)

### User Documentation

For complete user documentation refer [UserDocumentation.md](https://github.com/nisarg-vaghela/MediConnect/blob/master/docs/UserDocumentation.md)

