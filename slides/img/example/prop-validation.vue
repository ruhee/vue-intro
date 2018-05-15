export default {
  props: {
    someProp: Number,
    anotherProp: [String, Number],
    aThirdProp: {
      type: String,
      required: true,
      default: 'hi',
      validator: function (val) {
        return ['hi', 'hello'].indexOf(val) !== -1
      }
    }
  }
}

