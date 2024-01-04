require('child_process').exec('git log -1 --date=format:"%Y/%m/%d" --format="%ad"', function(err, stdout) {
    console.log(stdout);
});
