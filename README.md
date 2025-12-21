This project is based on [running_page](https://github.com/yihong0618/running_page) and adds support for multi sports types. Follow the steps in the origin repo to deploy.

## Custom your page

### Change Sports Color

- Modify Ride Color: `RIDE_COLOR` in `src/utils/const.js`

### Add Sports Type

- Modify `TYPE_DICT` & `MAPPING_TYPE` in `scripts/config.py`
- Add Type Name and add it into `RUN_TITLES` in `src/utils/const.js`
- Modify `colorFromType` & `titleForRun` in `src/utils/util.js`
- following steps: [commit](https://github.com/ben-29/workouts_page/commit/f3a35884d626009d33e05adc76bbc8372498f317)

---


# Special thanks

- @[yihong0618](https://github.com/yihong0618) for Awesome [running_page](https://github.com/yihong0618/running_page), Great Thanks
- @[ben-29](https://github.com/ben-29) for [different types support](https://github.com/ben-29/workouts_page) Appreciate!