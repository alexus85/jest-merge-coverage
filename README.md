# jest-merge-coverage
script to merge all coverage reports into one final report


const rootDir = './coverage/libs'; /// directory where youyr coverage reports are located
const reportOut = './coverage/report'; /// directory where the final report 
const reportTypes = ['html', 'text']; // types of reports to be exported
