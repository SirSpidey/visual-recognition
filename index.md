---

copyright:
  years: 2015, 2019
lastupdated: "2019-06-04"

keywords: Visual Recognition service,Face model,Food model,Explicit,Text recognition,Visual Recognition use cases

subcollection: visual-recognition

---

{:shortdesc: .shortdesc}
{:external: target="_blank" .external}
{:tip: .tip}
{:important: .important}
{:note: .note}
{:deprecated: .deprecated}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}

# About
{: #index}

On April 2, 2018, the identity information in the response to calls to the Face model was removed. The identity information refers to the name of the person, score, and type_hierarchy knowledge graph. For details about the enhanced Face model, see the [Release notes](/docs/services/visual-recognition?topic=visual-recognition-release-notes#2april2018).
{: deprecated}

The {{site.data.keyword.visualrecognitionfull}} service uses deep learning algorithms to analyze images for scenes, objects, faces, and other content. The response includes keywords that provide information about the content.
{: shortdesc}

## Available models
{: #models}

A set of built-in models provides highly accurate results without training:

- [**General** model](/docs/services/visual-recognition?topic=visual-recognition-customizing#general-model): Default classification from thousands of classes.
- [**Face** model](/docs/services/visual-recognition?topic=visual-recognition-getting-started-tutorial#detect-faces): Facial analysis with age and gender.
- **Explicit** model: Whether an image is inappropriate for general use.
- **Food** model: Specifically for images of food items.
- **Text** model (Private beta): Text extraction from natural scene images. [Request access](https://datasciencex.typeform.com/to/nU6efl){: external}.

You can also train [custom models](/docs/services/visual-recognition?topic=visual-recognition-tutorial-custom-classifier#tutorial-custom-classifier) to create specialized classes.

## How to use the service
{: #language-support-how-to}

The following image shows the process of creating and using {{site.data.keyword.visualrecognitionshort}}:

![Describes the flow of the {{site.data.keyword.visualrecognitionshort}} service, from preparing, training, and classifying images to viewing results.](images/visual-recognition-process-110717.svg)


## Use cases
{: #language-support-use-cases}

The {{site.data.keyword.visualrecognitionshort}} service can be used for diverse applications and industries, such as:

- **Manufacturing:** Use images from a manufacturing setting to make sure products are being positioned correctly on an assembly line
- **Visual auditing:** Look for visual compliance or deterioration in a fleet of trucks, planes, or windmills out in the field, train custom models to understand what defects look like
- **Insurance:** Rapidly process claims by using images to classify claims into different categories
- **Social listening:** Use images from your product line or your logo to track buzz about your company on social media
- **Social commerce:** Use an image of a plated dish to find out which restaurant serves it and find reviews, use a travel photo to find vacation suggestions based on similar experiences
- **Retail:** Take a photo of a favorite outfit to find stores with those clothes in stock or on sale, use a travel image to find retail suggestions in that area
- **Education:** Create image-based applications to educate about taxonomies
