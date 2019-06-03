<template>
  <div class="container">
    <div>
      <hr class="seperator">
      <div class="page-header text-center">
        <h1>News Page Prototype</h1>
      </div>
    </div>
    <div class="centered-block">
      <hr class="seperator">
      <div>
        <div class="boardz centered-block">
          <!--The number of ul's equates to the number of columns  -->
          <ul>This will be the sidebar eventually</ul>
          <!-- Column 1 -->
          <ul>
            <app-news-card
              :newsHeader="newsCard1.title"
              :newsBody="newsCard1.description"
              :blogURL="newsCard1.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard2.title"
              :newsBody="newsCard2.description"
              :blogURL="newsCard2.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard3.title"
              :newsBody="newsCard3.description"
              :blogURL="newsCard3.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard1.title"
              :newsBody="newsCard1.description"
              :blogURL="newsCard1.blogPostURL"
            ></app-news-card>
          </ul>
          <!-- Column 2 -->
          <ul>
            <app-news-card
              :newsHeader="newsCard2.title"
              :newsBody="newsCard2.description"
              :blogURL="newsCard2.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard3.title"
              :newsBody="newsCard3.description"
              :blogURL="newsCard3.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard1.title"
              :newsBody="newsCard1.description"
              :blogURL="newsCard1.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard2.title"
              :newsBody="newsCard2.description"
              :blogURL="newsCard2.blogPostURL"
            ></app-news-card>
          </ul>
          <!-- Column 3 -->
          <ul>
            <app-news-card
              :newsHeader="newsCard1.title"
              :newsBody="newsCard1.description"
              :blogURL="newsCard1.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard2.title"
              :newsBody="newsCard2.description"
              :blogURL="newsCard2.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard2.title"
              :newsBody="newsCard2.description"
              :blogURL="newsCard2.blogPostURL"
            ></app-news-card>
            <app-news-card
              :newsHeader="newsCard3.title"
              :newsBody="newsCard3.description"
              :blogURL="newsCard3.blogPostURL"
            ></app-news-card>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NewsCard from "./components/NewsCard.vue";

export default {
  //This data will eventually be pulled in from the database
  data: function() {
    return {
      // These are dummy data news cards
      newsCard1: {
        title: "Audire Integre",
        description:
          "It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy.",
        blogPostURL:
          "https://w3-connections.ibm.com/blogs/681bbedb-3892-4818-9961-38698c6ccde9/entry/Security_and_Privacy_for_Developers?lang=en_us"
      },
      newsCard2: {
        title: "Morbiso",
        description:
          "Morbi in sem quis dui placerat ornare. Pellentesque odio nisi, euismod in, pharetra a, ultricies in, diam. Sed arcu. Cras consequat.",
        blogPostURL:
          "https://w3-connections.ibm.com/blogs/925e2dd8-147c-4c30-a8a8-1339dd406ae9/entry/2019_F_SC_Hackathon_A_pouring_of_new_ideas_for_Financial_Systems?lang=en_us"
      },
      newsCard3: {
        title: "Vix Clita",
        description:
          "At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae.",
        blogPostURL:
          "https://w3-connections.ibm.com/blogs/681bbedb-3892-4818-9961-38698c6ccde9/entry/Hortolandia_DoJo_Workshop_with_immediate_result?lang=en_us"
      }
    };
  },
  components: {
    appNewsCard: NewsCard
  }
};
</script>

<style>
</style>

