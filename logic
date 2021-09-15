
  const autoComplete = (val, sug) => {


    const startArr = [];
    const includsArr = [];
    const exactArr = [];

    sug.forEach(s => {
      const start = s.startsWith(val)
      const include = s.includes(val)
      const exact = s === val

      if (exact) exactArr.push(s)
      else if (start) startArr.push(s)
      else if (include) includsArr.push(s)
    })

    return [...exactArr, ...startArr, ...includsArr]

  }
