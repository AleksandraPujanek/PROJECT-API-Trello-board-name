# :file_folder: PROJECT: API Trello - board name validation
Verification of REST API in Trello / create a new board with correct name (available characters and length) and E2E scenario.

**Summary:** [Trello - Test Report](https://drive.google.com/file/d/1WEboOLbMr4NWALqAs4NdX8bfnKXTYbLh/view?usp=drive_link)

**Tools:**
- Postman x86_64 10.19.7,
- Newman 6.0.0,
- Newman Reporter htmlextra 1.22.11.

**Environment:** Trello production [https://trello.com/](https://trello.com/)

**Postman Environment:** [TRELLO Prod.postman_environment.json](https://drive.google.com/file/d/17MM5R5H40Rii3WUDZgAQbNZw2OT2jxvu/view?usp=drive_link)

**Documentation:** [REST API Trello - documentation](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-post)

**Endpoint:** https://api.trello.com/1/boards

**Required Query Params:**
- name={name}
    - name (string)
    - 1 to 16384 characters long.
    - Min length: 1
    - Max length: 16384
- key=APIKey
- token=APIToken

## Collection #1 - P.1.Trello - board name tests [QueryParams]

**Test Data:**
- [P.1_2.TrelloBoardNamePositive.json](https://drive.google.com/file/d/1Dk6x6D84aH9lIoAvXT-x8rsVRmYbit5H/view?usp=drive_link)
- [P.1_2.TrelloBoardNameNegative.json](https://drive.google.com/file/d/1w-0a1irkWvm-cZ-w18uWi11MFqtrdBW-/view?usp=drive_link)

**Postman Collections:**
- [P.1.Trello - board name tests - QueryParams - positive.postman_collection.json](https://drive.google.com/file/d/1YMIxFsuVzA6m2y2U_3UHpAfQ8U7tTNU7/view?usp=drive_link)
- [P.1.Trello - board name tests - QueryParams - negative.postman_collection.json](https://drive.google.com/file/d/19FzL6SFdaaKoeve6OfAo25LAJFsd-GMI/view?usp=drive_link)

**Reports:**
- [P.1.Trello - board name tests - QueryParams - positive_report.html](https://drive.google.com/file/d/1oEbkyK-6I6if8X3sDYxLJqaAL8M5vXLx/view?usp=drive_link)
- [P.1.Trello - board name tests - QueryParams - negative_report.html](https://drive.google.com/file/d/12z0n4Lf93NclgvUoMHuOA4G6Kb9KFqtw/view?usp=drive_link)

**Defect report:**
- [P.1.Trello - board name tests - QueryParams - defect report.xlsx](https://docs.google.com/spreadsheets/d/1398HPZYEmQ9QQNxpGLPKTvnsaAFhvIun/edit?usp=drive_link&ouid=105556741090660469965&rtpof=true&sd=true)


## Collection #2 - P.2.Trello - board name tests [json body]

**Test Data:**
- [P.1_2.TrelloBoardNamePositive.json](https://drive.google.com/file/d/1Dk6x6D84aH9lIoAvXT-x8rsVRmYbit5H/view?usp=drive_link)
- [P.1_2.TrelloBoardNameNegative.json](https://drive.google.com/file/d/1w-0a1irkWvm-cZ-w18uWi11MFqtrdBW-/view?usp=drive_link)

**Postman Collections:**
- [P.2.Trello - board name tests - json body - positive.postman_collection.json](https://drive.google.com/file/d/1FiDwpvIoTylZGtJrlyrPQhTzi_NBZcxO/view?usp=drive_link)
- [P.2.Trello - board name tests - json body - negative.postman_collection.json](https://drive.google.com/file/d/1HLpjCMaLiHbojX-Zwip_f1rKerD7T2cq/view?usp=drive_link)

**Reports:**
- [P.2.Trello - board name tests - json body - positive_report.html](https://drive.google.com/file/d/1GnymfUo6T1sToO1w94Y38Ksdh9a7udHf/view?usp=drive_link)
- [P.2.Trello - board name tests - json body - negative_report.html](https://drive.google.com/file/d/1MNvIgZwbVMCnh9EHeW-FGRqJO3Qw4Bm-/view?usp=drive_link)

## Collection #3 - P.3.Trello - board name length tests [json body]

**Test Data:**
- [P.3.TrelloBoardNameLengthPositive.json](https://drive.google.com/file/d/1C_lfp5nLYZfOfwkjet11W1rdElSq0wb1/view?usp=drive_link)
- [P.3.TrelloBoardNameLengthNegative.json](https://drive.google.com/file/d/1WS3gZmo4_hDfVvBmy1gWxvgWRG5296UZ/view?usp=drive_link)

**Postman Collections:**
- [P.3.Trello - board name length tests - json body - positive.postman_collection.json](https://drive.google.com/file/d/1b3fVL7fN4FFMDxmcpW3vT5J-IBumYlZN/view?usp=drive_link)
- [P.3.Trello - board name length tests - json body - negative.postman_collection.json](https://drive.google.com/file/d/1sYbQcYkfzMiw2vHuIe0vkgIF-5wYRap4/view?usp=drive_link)

**Reports:**
- [P.3.Trello - board name length tests - json body - positive_report.html](https://drive.google.com/file/d/1tu7Ku9yGaOncyFz6EwQ0Xs2fch9ijbXm/view?usp=drive_link)
- [P.3.Trello - board name length tests - json body - negative_report.html](https://drive.google.com/file/d/1RQl8llWePthWaT_Z8sp16oyOjfKHpL8v/view?usp=drive_link)

## Collection #4 - P.4.Trello - board name length tests [QueryParams]

**Test Data:**
- [P.4.TrelloBoardNameLength.json](https://drive.google.com/file/d/1mojGpljVZPb9qDzlwg3YOmzxdYuGLKc0/view?usp=drive_link)

**Postman Collections:**
- [P.4.Trello - board name length tests - QueryParams - positive.postman_collection.json](https://drive.google.com/file/d/1vUdeTJY99LldDihnElxxrKBjAmJ4_N5K/view?usp=drive_link)

**Reports:**
- [P.4.Trello - board name length tests - QueryParams - positive_report.html](https://drive.google.com/file/d/14K90HbwKOvs5JElCQ5_we0rztc5ZZ5qk/view?usp=drive_link)

**Defect report:**
- [P.4.Trello - board name length tests - QueryParams - defect report.xlsx](https://docs.google.com/spreadsheets/d/1nsYtfU4DmQzDb1kyzSFH3jafBvj79WTB/edit?usp=drive_link&ouid=105556741090660469965&rtpof=true&sd=true)
