<template>
  <div class="hero-header78">
    <div class="hero-column thq-section-padding thq-section-max-width">
      <div class="hero-content1">
        <h1 class="hero-text1 thq-heading-1">{{ heading1 }}</h1>
        <p class="hero-text2 thq-body-large">{{ content1 }}</p>
      </div>
      <div class="hero-actions">
        <button class="thq-button-filled hero-button1">
          <span class="thq-body-small">{{ action1 }}</span>
        </button>
        <button class="thq-button-outline hero-button2">
          <span class="thq-body-small">{{ action2 }}</span>
        </button>
      </div>
    </div>
    <div class="hero-content2">
      <div
        class="hero-row-container1 thq-animated-group-container-horizontal thq-mask-image-horizontal"
      >
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero-placeholder-image10 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero-placeholder-image11 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero-placeholder-image12 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero-placeholder-image13 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero-placeholder-image14 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image6Alt"
            :src="image6Src"
            class="hero-placeholder-image15 thq-img-ratio-1-1 thq-img-scale"
          />
        </div>
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero-placeholder-image16 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero-placeholder-image17 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero-placeholder-image18 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero-placeholder-image19 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero-placeholder-image20 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1534312527009-56c7016453e6?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDIxfHxhYnN0cmFjdHxlbnwwfHx8fDE3MTA4NzA5MzB8MA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero-placeholder-image21 thq-img-ratio-1-1 thq-img-scale"
          />
        </div>
      </div>
      <div
        class="hero-row-container2 thq-animated-group-container-horizontal thq-mask-image-horizontal"
      >
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero-placeholder-image22 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero-placeholder-image23 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero-placeholder-image24 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image10Alt"
            :src="image10Src"
            class="hero-placeholder-image25 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero-placeholder-image26 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image12Alt"
            :src="image12Src"
            class="hero-placeholder-image27 thq-img-ratio-1-1 thq-img-scale"
          />
        </div>
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero-placeholder-image28 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero-placeholder-image29 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero-placeholder-image30 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image10Alt"
            :src="image10Src"
            class="hero-placeholder-image31 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero-placeholder-image32 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1568214379698-8aeb8c6c6ac8?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDEyfHxncmFmaWN8ZW58MHx8fHwxNzE1Nzk0OTk5fDA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero-placeholder-image33 thq-img-ratio-1-1 thq-img-scale"
          />
        </div>
      </div>
    </div>
    <div>
      <div class="hero-container2">
        <DangerousHTML
          html="<style>
    @keyframes scroll-x {
      from {
        transform: translateX(0);
      }
      to {
        transform: translateX(calc(-100% - 16px));
      }
    }
  
    @keyframes scroll-y {
      from {
        transform: translateY(0);
      }
      to {
        transform: translateY(calc(-100% - 16px));
      }
    }
  </style>
  "
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

export default {
  name: 'Hero',
  props: {
    image11Alt: {
      type: String,
      default: 'Hero Image',
    },
    action1: {
      type: String,
      default: 'Main action',
    },
    image9Alt: {
      type: String,
      default: 'Hero Image',
    },
    image4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1603354350317-6f7aaa5911c5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image8Alt: {
      type: String,
      default: 'Hero Image',
    },
    image5Alt: {
      type: String,
      default: 'Hero Image',
    },
    image2Alt: {
      type: String,
      default: 'Hero Image',
    },
    image11Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1503641527561-d776d4deee48?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4MXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1519406596751-0a3ccc4937fe?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4MXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image7Alt: {
      type: String,
      default: 'Hero Image',
    },
    image10Alt: {
      type: String,
      default: 'Hero Image',
    },
    image6Alt: {
      type: String,
      default: 'Hero Image',
    },
    image8Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1505330622279-bf7d7fc918f4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1656087815769-89dd3c82f767?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU3OHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image1Alt: {
      type: String,
      default: 'Hero Image',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1609345635744-a58486ce86cd?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4NHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1497633762265-9d179a990aa6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU3OXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image6Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1584697964479-60a5a1d11307?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image12Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1532012197267-da84d127e765?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1462536943532-57a629f6cc60?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    action2: {
      type: String,
      default: 'Secondary action',
    },
    image3Alt: {
      type: String,
      default: 'Hero Image',
    },
    image9Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1629470937874-f3c7ddc525af?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4Mnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image12Alt: {
      type: String,
      default: 'Hero Image',
    },
    heading1: {
      type: String,
      default: 'Medium length hero headline goes here',
    },
    image4Alt: {
      type: String,
      default: 'Hero Image',
    },
    content1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat.',
    },
    image10Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1554774853-719586f82d77?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcyNDEzMjU4M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
  },
  components: {
    DangerousHTML,
  },
}
</script>

<style scoped>
.hero-header78 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.hero-column {
  gap: var(--dl-space-space-oneandhalfunits);
  width: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
.hero-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.hero-text1 {
  text-align: center;
}
.hero-text2 {
  text-align: center;
}
.hero-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
}
.hero-content2 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.hero-row-container1 {
  width: 100%;
}
.hero-placeholder-image10 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image11 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image12 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image13 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image14 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image15 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image16 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image17 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image18 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image19 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image20 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image21 {
  width: 400px;
  height: 400px;
}
.hero-row-container2 {
  width: 100%;
}
.hero-placeholder-image22 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image23 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image24 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image25 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image26 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image27 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image28 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image29 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image30 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image31 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image32 {
  width: 400px;
  height: 400px;
}
.hero-placeholder-image33 {
  width: 400px;
  height: 400px;
}
.hero-container2 {
  display: contents;
}
@media(max-width: 767px) {
  .hero-content2 {
    width: 100%;
  }
}
@media(max-width: 479px) {
  .hero-actions {
    width: 100%;
    flex-direction: column;
  }
  .hero-button1 {
    width: 100%;
  }
  .hero-button2 {
    width: 100%;
  }
}
</style>
