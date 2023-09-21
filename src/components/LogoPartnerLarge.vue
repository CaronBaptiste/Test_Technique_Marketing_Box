    <template> 
    <div>   
            <img
              :src="logo"
              alt=""
            />
    </div> 
  </template>
  
  <script>
  export default {
    name: "LogoPartnerLarge",
    props:{
            logo:{
                type: String,
                required: true
            },
        }
    }
  </script>
  
  <style scoped>
 
  </style>
  