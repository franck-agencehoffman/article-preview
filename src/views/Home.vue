<template>
  <div class="page-wrapper">
    <article class="article-preview">
      <div class="visual-container"></div>
      <div class="content-container">
        <div class="content">
          <h2 class="big-title">Shift the overall look and feel by adding these wonderful touches to furniture in your home</h2>
          <p class="regular-text">Ever been in a room and felt like something was missing? Perhaps it felt slightly bare and uninviting. I’ve got some simple tips to help you make any room feel complete.</p>
        </div>

        <div class="footer">
          <div class="author">
            <img class="photo" src="@/assets/img/article-visual.png">
            <div class="details">
              <h3 class="small-title">Michelle Appleton</h3>
              <p class="small-text">28 Jun 2020</p>
            </div>
          </div>

          <div class="share-actions">
            <p class="share-text">SHARE</p>
            <div class="share-socials">
              <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M18.8958 0H1.10417C0.494167 0 0 0.494167 0 1.10417V18.8967C0 19.5058 0.494167 20 1.10417 20H10.6833V12.255H8.07667V9.23667H10.6833V7.01083C10.6833 4.4275 12.2608 3.02083 14.5658 3.02083C15.67 3.02083 16.6183 3.10333 16.895 3.14V5.84L15.2967 5.84083C14.0433 5.84083 13.8008 6.43667 13.8008 7.31V9.2375H16.79L16.4008 12.2558H13.8008V20H18.8975C19.5058 20 20 19.5058 20 18.8958V1.10417C20 0.494167 19.5058 0 18.8958 0Z" fill="white"/>
              </svg>
              <svg width="20" height="17" viewBox="0 0 20 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M20 2.17221C19.2642 2.49888 18.4733 2.71888 17.6433 2.81805C18.4908 2.31055 19.1417 1.50638 19.4475 0.548047C18.655 1.01805 17.7767 1.35971 16.8417 1.54388C16.0942 0.74638 15.0267 0.248047 13.8467 0.248047C11.1975 0.248047 9.25083 2.71971 9.84917 5.28555C6.44 5.11471 3.41667 3.48138 1.3925 0.99888C0.3175 2.84305 0.835 5.25555 2.66167 6.47721C1.99 6.45555 1.35667 6.27138 0.804167 5.96388C0.759167 7.86471 2.12167 9.64305 4.095 10.0389C3.5175 10.1955 2.885 10.2322 2.24167 10.1089C2.76333 11.7389 4.27833 12.9247 6.075 12.958C4.35 14.3105 2.17667 14.9147 0 14.658C1.81583 15.8222 3.97333 16.5014 6.29 16.5014C13.9083 16.5014 18.2125 10.0672 17.9525 4.29638C18.7542 3.71721 19.45 2.99471 20 2.17221Z" fill="white"/>
              </svg>
              <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M10 0C4.4775 0 0 4.47667 0 10C0 14.2367 2.63583 17.855 6.35583 19.3117C6.26833 18.5208 6.18917 17.3075 6.39083 16.4442C6.5725 15.6633 7.56333 11.4733 7.56333 11.4733C7.56333 11.4733 7.26417 10.8742 7.26417 9.98833C7.26417 8.59833 8.07 7.56 9.07333 7.56C9.92583 7.56 10.3383 8.20083 10.3383 8.96833C10.3383 9.82583 9.7925 11.1083 9.51 12.2975C9.27417 13.2925 10.0092 14.105 10.9908 14.105C12.7683 14.105 14.1342 12.2308 14.1342 9.52583C14.1342 7.13167 12.4142 5.4575 9.9575 5.4575C7.1125 5.4575 5.4425 7.59167 5.4425 9.79667C5.4425 10.6558 5.77333 11.5783 6.18667 12.0783C6.26833 12.1775 6.28 12.265 6.25583 12.3658L5.97833 13.4992C5.93417 13.6825 5.83333 13.7217 5.64333 13.6333C4.39417 13.0517 3.61333 11.2258 3.61333 9.75917C3.61333 6.605 5.905 3.7075 10.2208 3.7075C13.69 3.7075 16.3858 6.18 16.3858 9.48333C16.3858 12.93 14.2133 15.7033 11.1967 15.7033C10.1833 15.7033 9.23083 15.1775 8.905 14.555L8.28167 16.9325C8.05583 17.8017 7.44667 18.8908 7.03833 19.5542C7.975 19.8433 8.96917 20 10 20C15.5225 20 20 15.5225 20 10C20 4.47667 15.5225 0 10 0Z" fill="white"/>
              </svg>
            </div>

            <button class="share-btn" type="button" @click="toggleSharing">
              <svg width="15" height="13" viewBox="0 0 15 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M15 6.49504L8.76629 0.013916V3.88067H7.44095C3.33138 3.88067 0 7.03931 0 10.9358V12.9849L0.588684 12.3733C2.59014 10.2941 5.4221 9.1094 8.39115 9.1094H8.76629V12.9762L15 6.49504Z" fill="#6E8098"/>
              </svg>
            </button>
          </div>

          <div class="share-wrapper">
            <button class="share-btn" type="button" @click="toggleSharing">
              <svg width="15" height="13" viewBox="0 0 15 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M15 6.49504L8.76629 0.013916V3.88067H7.44095C3.33138 3.88067 0 7.03931 0 10.9358V12.9849L0.588684 12.3733C2.59014 10.2941 5.4221 9.1094 8.39115 9.1094H8.76629V12.9762L15 6.49504Z" fill="#6E8098"/>
              </svg>
            </button>

            <div class="share-tooltip">
              <p class="share-text">SHARE</p>
              <div class="share-socials">
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M18.8958 0H1.10417C0.494167 0 0 0.494167 0 1.10417V18.8967C0 19.5058 0.494167 20 1.10417 20H10.6833V12.255H8.07667V9.23667H10.6833V7.01083C10.6833 4.4275 12.2608 3.02083 14.5658 3.02083C15.67 3.02083 16.6183 3.10333 16.895 3.14V5.84L15.2967 5.84083C14.0433 5.84083 13.8008 6.43667 13.8008 7.31V9.2375H16.79L16.4008 12.2558H13.8008V20H18.8975C19.5058 20 20 19.5058 20 18.8958V1.10417C20 0.494167 19.5058 0 18.8958 0Z" fill="white"/>
                </svg>
                <svg width="20" height="17" viewBox="0 0 20 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M20 2.17221C19.2642 2.49888 18.4733 2.71888 17.6433 2.81805C18.4908 2.31055 19.1417 1.50638 19.4475 0.548047C18.655 1.01805 17.7767 1.35971 16.8417 1.54388C16.0942 0.74638 15.0267 0.248047 13.8467 0.248047C11.1975 0.248047 9.25083 2.71971 9.84917 5.28555C6.44 5.11471 3.41667 3.48138 1.3925 0.99888C0.3175 2.84305 0.835 5.25555 2.66167 6.47721C1.99 6.45555 1.35667 6.27138 0.804167 5.96388C0.759167 7.86471 2.12167 9.64305 4.095 10.0389C3.5175 10.1955 2.885 10.2322 2.24167 10.1089C2.76333 11.7389 4.27833 12.9247 6.075 12.958C4.35 14.3105 2.17667 14.9147 0 14.658C1.81583 15.8222 3.97333 16.5014 6.29 16.5014C13.9083 16.5014 18.2125 10.0672 17.9525 4.29638C18.7542 3.71721 19.45 2.99471 20 2.17221Z" fill="white"/>
                </svg>
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M10 0C4.4775 0 0 4.47667 0 10C0 14.2367 2.63583 17.855 6.35583 19.3117C6.26833 18.5208 6.18917 17.3075 6.39083 16.4442C6.5725 15.6633 7.56333 11.4733 7.56333 11.4733C7.56333 11.4733 7.26417 10.8742 7.26417 9.98833C7.26417 8.59833 8.07 7.56 9.07333 7.56C9.92583 7.56 10.3383 8.20083 10.3383 8.96833C10.3383 9.82583 9.7925 11.1083 9.51 12.2975C9.27417 13.2925 10.0092 14.105 10.9908 14.105C12.7683 14.105 14.1342 12.2308 14.1342 9.52583C14.1342 7.13167 12.4142 5.4575 9.9575 5.4575C7.1125 5.4575 5.4425 7.59167 5.4425 9.79667C5.4425 10.6558 5.77333 11.5783 6.18667 12.0783C6.26833 12.1775 6.28 12.265 6.25583 12.3658L5.97833 13.4992C5.93417 13.6825 5.83333 13.7217 5.64333 13.6333C4.39417 13.0517 3.61333 11.2258 3.61333 9.75917C3.61333 6.605 5.905 3.7075 10.2208 3.7075C13.69 3.7075 16.3858 6.18 16.3858 9.48333C16.3858 12.93 14.2133 15.7033 11.1967 15.7033C10.1833 15.7033 9.23083 15.1775 8.905 14.555L8.28167 16.9325C8.05583 17.8017 7.44667 18.8908 7.03833 19.5542C7.975 19.8433 8.96917 20 10 20C15.5225 20 20 15.5225 20 10C20 4.47667 15.5225 0 10 0Z" fill="white"/>
                </svg>
              </div>
              <i></i>
            </div>
          </div>
        </div>
      </div>
    </article>
  </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
  head() {
    return {
      title: {
        inner: 'Home'
      },
      meta: [
        {
          name: 'description',
          content: `${this.appTitle} home page`,
          id: 'desc'
        }
      ]
    }
  },
  computed: mapState('app', ['appTitle']),
  methods: {
    toggleSharing() {
      // if (window.innerWidth <= 799) {
        const footer = document.querySelector('.footer')

        footer.classList.toggle('is-sharing')
      // }
    }
  }
}
</script>

<style lang="scss" scoped>
@import '@/theme/variables.scss';

.page-wrapper {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: $light;

  @media (max-width: 768px) {
    padding: 24px
  }
}

.article-preview {
  display: flex;
  align-items: stretch;
  width: 100%;
  max-width: 730px;
  margin: 0 auto;
  border-radius: 10px;
  background: $white;
  box-shadow: 0 40px 40px -10px rgba(201, 213, 225, 0.503415);

  @media (max-width: 599px) {
    position: relative;
    overflow: hidden;
    max-width: 100%;
    flex-direction: column;
  }

  .visual-container {
    width: 100%;
    max-width: 285px;
    height: 280px;
    border-radius: 10px 0 0 10px;
    background-repeat: no-repeat;
    background-position: left bottom;
    background-size: cover;
    background-image: url('../assets/img/article-preview-background.jpg');

    @media (max-width: 599px) {
      max-width: 100%;
      height: 280px;
      border-radius: 10px 10px 0 0;
    }
  }

  .content {
    padding: 32px 40px 10px;

    @media (max-width: 599px) {
      padding: 36px 32px 16px;
    }
  }

  .big-title {
    margin: 0 0 12px;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 28px;
    letter-spacing: 0.25px;
    color: $textDark;

    @media (max-width: 599px) {
      font-size: 16px;
      line-height: 24px;
      letter-spacing: 0.2px;
    }
  }

  .regular-text {
    margin: 0;
    font-style: normal;
    font-weight: 500;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0.121875px;
    color: $textGrey;
  }

  .small-title {
    margin: 0;
    font-style: normal;
    font-style: normal;
    font-weight: bold;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0.121875px;
    color: $textDark;
  }

  .small-text {
    margin: 0;
    font-style: normal;
    font-weight: 500;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0.121875px;
    color: $textLight;
  }

  .footer {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 40px 32px;

    @media (max-width: 599px) {
      padding: 16px 32px;
    }

    &.is-sharing {
      .share-btn {
        background: $textGrey;

        svg path {
          fill: $white;
        }
      }

      .share-actions {
        @media (max-width: 768px) {
          display: flex;
        }
      }

      .share-wrapper {
        .share-btn {
          display: none;
        }
      }
    }

    .author {
      display: flex;
      align-items: center;
    }

    .details {
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-left: 16px;
    }
  }

  .share-actions {
    position: absolute;
    inset: 0;
    display: none;
    padding-left: 32px;
    padding-right: 32px;
    background-color: $dark;

    @media (max-width: 768px) {
      display: none;
      align-items: center;
    }

    .share-text {
      margin: 0 21px 0 0;
      font-style: normal;
      font-weight: 500;
      font-size: 13px;
      line-height: 20px;
      letter-spacing: 5px;
      color: $textLight;
    }

    .share-socials {
      display: flex;
      align-items: center;

      svg {
        margin-right: 16px;

        &:last-of-type {
          margin-right: 0;
        }
      }
    }

    .share-btn {
      position: relative;
      z-index: 5;
      margin-left: auto;
    }
  }

  .share-btn {
    width: 32px;
    height: 32px;
    border-radius: 50%;
    border: 0;
    background: $light;
    appearance: none;
  }

  .share-wrapper {
    position: relative;
    display: inline-block;
    text-align: left;

    &:hover {
      .share-btn {
        background: $textGrey;

        svg path {
          fill: $white;
        }
      }

      .share-tooltip {
        display: flex;

        @media (max-width: 768px) {
          display: none;
        }
      }
    }

    .share-btn {
      position: relative;

      @media (max-width: 768px) {
        z-index: 0;
      }
    }

    .share-tooltip {
      position: absolute;
      z-index: 100;
      display: none;
      align-items: center;
      top: -20px;
      left: 50%;
      min-width: 200px;
      max-width: 400px;
      padding: 17px 36px;
      border-radius: 10px;
      background-color: $dark;
      box-sizing: border-box;
      box-shadow: 0 10px 10px rgba(201, 213, 225, 0.503415);
      transform: translate(-30%,-100%);

      @media (max-width: 599px) {
        display: none;
      }

      .share-text {
        margin: 0 21px 0 0;
        font-style: normal;
        font-weight: 500;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 5px;
        color: $textLight;
      }

      .share-socials {
        display: flex;
        align-items: center;

        svg {
          margin-right: 16px;

          &:last-of-type {
            margin-right: 0;
          }
        }
      }

      i {
        position: absolute;
        overflow: hidden;
        top: 100%;
        left: 30%;
        width: 30px;
        height: 15px;
        margin-left: -15px;

        &::after {
          content: '';
          position: absolute;
          left: 50%;
          width: 15px;
          height: 15px;
          background-color: $dark;
          box-shadow: 0 10px 10px rgba(201, 213, 225, 0.503415);
          transform: translate(-50%,-50%) rotate(45deg);
        }
      }
    }
  }
}
</style>
