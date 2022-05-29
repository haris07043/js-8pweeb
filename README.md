# js-8pweeb

## Main Filter
  let group = activity.reduce((r, a) => {
    r[a.EmployeeID] = [...r[a.EmployeeID] || [], a];
    return r;
   }, {});
   console.log("group", group);