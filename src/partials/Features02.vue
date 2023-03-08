<template>
  <section>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="py-12 md:py-20">

        <!-- Section header -->
        <div class="max-w-3xl mx-auto text-center pb-12 md:pb-16">
          <h2 class="h2 font-cabinet-grotesk">Celebrating Culture, Standing Up for Justice, and Supporting Those Affected by the Mai Tangale Crisis</h2>
        </div>

        <div>

          <!-- Category buttons -->
          <div class="pb-12 md:pb-20">
            <div class="flex flex-wrap justify-center -m-1.5">
              <button class="btn-sm m-1.5 h-8 shadow" :class="category === '1' ? 'bg-blue-500 text-white' : 'bg-white text-gray-900 hover:bg-blue-50'" @click="category = '1'">Donation</button>
              <button class="btn-sm m-1.5 h-8 shadow" :class="category === '2' ? 'bg-blue-500 text-white' : 'bg-white text-gray-900 hover:bg-blue-50'" @click="category = '2'">About ShagBai</button>
              <button class="btn-sm m-1.5 h-8 shadow" :class="category === '3' ? 'bg-blue-500 text-white' : 'bg-white text-gray-900 hover:bg-blue-50'" @click="category = '3'">Tangale</button>
              <button class="btn-sm m-1.5 h-8 shadow" :class="category === '4' ? 'bg-blue-500 text-white' : 'bg-white text-gray-900 hover:bg-blue-50'" @click="category = '4'">Cultural Center</button>
            </div>
          </div>

          <!-- Section content -->
          <div class="max-w-xl mx-auto md:max-w-none flex flex-col md:flex-row md:space-x-8 lg:space-x-16 xl:space-x-20 space-y-8 space-y-reverse md:space-y-0">

            <!-- Content -->
            <div class="md:w-7/12 lg:w-1/2 order-1 md:order-none" data-aos="fade-up">
              <!-- Content #1 -->
              <div v-show="category === '1'">
                <h3 class="h3 font-cabinet-grotesk mb-3">The Tangle Community Needs You</h3>
                <p class="text-lg text-gray-500 mb-8">The Mai Tangale Crisis has caused unimaginable hardship for many families in our community. Breadwinners have been arrested and detained without proof or due cause, leaving their loved ones struggling to make ends meet. These families are counting on us to provide the support and assistance they need to get through this difficult time.</p>
                <ul class="inline-flex flex-col space-y-6">
                  <li class="flex items-start">
                    <svg class="w-3 h-3 fill-current text-blue-500 mt-1.5 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <div>
                      <div class="font-cabinet-grotesk font-bold text-lg mb-1">Act Now and Make a Difference</div>
                      <div class="text-gray-500">
                        That's why we, the ShagBai Team, are calling on all sons and daughters of Tangale to donate to the Appeal Fund and show our solidarity with these families. Every dollar you donate will go directly towards helping these families get through this crisis.
                      </div>
                    </div>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-3 h-3 fill-current text-blue-500 mt-1.5 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <div>
                      <div class="font-cabinet-grotesk font-bold text-lg mb-1">Even a Small Donation Can Help</div>
                      <div class="text-gray-500">
                        We know that times are tough, but even a small donation can make a huge impact. Whether you can donate a little or a lot, every bit helps. So please, take action now and donate to the Appeal Fund. Together, we can demonstrate the power of our community to make a difference and show our support for these families in need.
                      </div>
                    </div>
                  </li>
                  <li class="flex items-start">
                    <svg class="w-3 h-3 fill-current text-blue-500 mt-1.5 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                      <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                    </svg>
                    <div>
                      <div class="font-cabinet-grotesk font-bold text-lg mb-1">Multiple Donation Options Available</div>
                      <div class="text-gray-500">
                       You have several options for donating to the Appeal Fund, including cash, bank transfer, USSD code, online, or offline. We are accepting funds through the account of Maikwada Maikenti - for the ShagBai Team. Don't wait any longer - make your donation now and help support these families in need..</div>
                    </div>
                  </li>
                </ul>
              </div>
              <!-- Content #2 -->
              <div v-show="category === '2'">
                <h3 class="h3 font-cabinet-grotesk mb-3">About ShagBai Festival</h3>
                <p class="text-lg text-gray-500 mb-6">
                  The ShagBai Festival is an annual event that takes place in the Billiri local government area of Gombe state, Nigeria. It is a celebration of the dog meat culture and a time for members of the Tangale community to come together and enjoy traditional dance and music performances, food, and other activities. The festival was first held in December 2021 and was so well-received that it was decided to hold it again on January 1st and 2nd of the following year. </p>
<p class="text-lg text-gray-500 mb-6">Convened by Hon. Jesse Amos Malums (Mai Balla), the festival has become a beloved tradition for many in the Tangale community. The festival starts with a rally at the dog market and continues with various events and activities throughout the city of Billiri. The ShagBai festival offers a unique opportunity for individuals interested in dog meat culture to come together and celebrate, as well as learn more about this important aspect of Tangale culture.</p>
<p class="text-lg text-gray-500 mb-6">In addition to the traditional elements of the festival, this year's ShagBai festival will also have a focus on Tangale youth and culture, as well as Tangale politics. There will be panel discussions and other opportunities for young leaders from Tangle to engage in meaningful conversations about their role in shaping the political landscape of their community. There will also be traditional dance and music performances, showcasing the talents and traditions of the young people of Tangle. </p>
<p class="text-lg text-gray-500 mb-6">The ShagBai festival also has a more serious purpose this year, as one of its main objectives is to raise funds for the families of those who have been affected by the Mai Tangale Crisis. Many individuals, including women and children, have been arrested and detained without proof or due cause, and their families are struggling to make ends meet. The ShagBai team is committed to supporting these families and providing them with the help and assistance they need. </p>
<p class="text-lg text-gray-500 mb-6">We encourage all members of the Tangale community to come out and support the ShagBai festival, either by attending in person or by making a donation to the Appeal Fund. This festival is a unique and special celebration of Tangale culture and heritage, as well as a time to come together and show our solidarity with those affected by the Mai Tangale Crisis. Join us for a truly unforgettable event and experience the rich cultural heritage of Tangle!</p>
              </div>
              <!-- Content #3 -->
              <div v-show="category === '3'">
                <h3 class="h3 font-cabinet-grotesk mb-3">Brief History of the Tangale People</h3>
                <p class="text-lg text-gray-500 mb-6">
                  The Tangale people are an ethnic group found in Gombe State in northeastern Nigeria. They speak the Tangale language, which belongs to the West Chadic group of the Afro-Asiatic language family.</p>
<p class="text-lg text-gray-500 mb-6" >According to oral tradition, the Tangale people migrated to their current location in the early 19th century. They traditionally lived in small, dispersed settlements and engaged in activities such as farming, herding, and trade. These traditional economic activities continue to play a significant role in the lives of many Tangale people, although many have also found employment in other sectors such as government, education, and business.</p>
<p class="text-lg text-gray-500 mb-6">The Tangale people have a rich cultural heritage, including a strong oral tradition and a variety of artistic and craft traditions. Their music and dance are an important part of their cultural identity and are enjoyed at events such as weddings and religious festivals. The Tangale people are also known for their skills in basket-weaving and pottery-making, and these crafts play an important role in the local economy.</p>
<p class="text-lg text-gray-500 mb-6">In the post-colonial period, the Tangale people have faced challenges such as poverty, conflict, and limited access to education and healthcare. Despite these challenges, the Tangale people have maintained a strong cultural identity and continue to make important contributions to the social and economic development of Gombe State.</p>
<p class="text-lg text-gray-500 mb-6">Overall, the Tangale people have a long and fascinating history and continue to play a vital role in the cultural and economic life of Gombe State and Nigeria.</p>  
                </div>
              <!-- Content #4 -->
              <div v-show="category === '4'">
                <h3 class="h3 font-cabinet-grotesk mb-3">Tibilthu Lar Mu Tangle Cultural Event Center.</h3>
                <p class="text-lg text-gray-500 mb-6">
                  The ShagBai Team is excited to announce our collaboration with the TCDA to bring the Tibilthu Lar Mu Tangle Cultural Event Center to life. This cultural center will be a gathering place for the youth of Tangle, offering a space for them to come together and learn about their culture, engage in political discussions, participate in dance and song, and so much more. </p>
<p class="text-lg text-gray-500 mb-6">One of the key features of the cultural center will be a focus on Tangale film and documentary. We believe that these mediums are a powerful way to share our stories and history with the world, and we are committed to supporting and promoting Tangale filmmakers. In addition to film and documentary, the cultural center will also offer opportunities for learning about the Tangale language and history. We believe that it is important for our youth to understand and appreciate their heritage, and we are dedicated to providing a space where they can do just that.</p>
<p class="text-lg text-gray-500 mb-6">Our team is committed to working with all stakeholders to ensure that this project becomes a reality. We are currently in the process of acquiring a suitable land for the center, and we are dedicated to creating a space that truly reflects the needs and interests of the Tangle youth. We believe that the Tibilthu Lar Mu Tangle Cultural Event Center will be a valuable asset for our community, and we are excited to see what the future holds. </p>
<p class="text-lg text-gray-500 mb-6">We encourage all members of the Tangle community to get involved and join us in this effort. Whether you are interested in donating to the project, volunteering your time and skills, or simply spreading the word, every little bit helps. We look forward to seeing you at the Tibilthu Lar Mu Tangle Cultural Event Center in the near future. Get ready for an exciting new chapter in Tangle culture!</p>
              </div>
            </div>

            <!-- Image -->
            <div class="md:w-5/12 lg:w-1/2" data-aos="fade-up" data-aos-delay="100">
              <img class="mx-auto md:max-w-none" src="../images/Logo.jpg" width="540" height="405" alt="Features" />
            </div>

          </div>

        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Features02',
  data: function () {
    return {
      category: '1'
    }
  },
}
</script>