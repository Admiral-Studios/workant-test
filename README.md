# Workant Test (React + TypeScript + Vite)

## Developers notes

- We decided not to display different IDs, since this information is not informative for the end user. Therefore, we have reduced the number of parameters that we display in the table.

### What exactly was removed:

- Users table:

  - id
  - roleId
  - country
  - subdepartment
  - group
  - division

- Time sheet table:

  - note
  - locationChecked

- We tried to make the tables as informative and user-friendly as possible: we added tooltips to all icons and displayed icons instead of words. This makes the table easier to interact with. By clicking on the eye icon, you can go to a detailed table by user and filter by month and required year.
- We have also added sorting for some columns to make searching for the required user or date as convenient and quick as possible. Since the tables are quite large and contain a lot of information, we’ve decided to make the first column fixed so that the user does not have problems with losing the necessary line.

## Libs

- axios
- bootstrap/react-bootstrap
- clsx
- typescript
- axios
