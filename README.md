# Numpy Tutorial
Numpy Tutorial for Beginner

<img alt="NumPy" src="https://cdn.rawgit.com/numpy/numpy/master/branding/icons/numpylogo.svg" height="60">

### NumPy is the fundamental package needed for scientific computing with Python.

It provides:

- a powerful N-dimensional array object
- sophisticated (broadcasting) functions
- tools for integrating C/C++ and Fortran code
- useful linear algebra, Fourier transform, and random number capabilities

This repogistory is a beginner tutorial for you, who want to quickly learn and start using Numpy for scientific computing. The tutorial is inside the **[notebook file](numpy.ipynb)**.

## Table of Contents
*   <span>[<span class="toc-item-num">1  </span>NumPy = Numerical Python](#NumPy-=-Numerical-Python)</span>
*   <span>[<span class="toc-item-num">2  </span>The Numpy ndarray: A Multidimensional Array Object](#The-Numpy-ndarray:-A-Multidimensional-Array-Object)</span>
    *   <span>[<span class="toc-item-num">2.1  </span>NumPy Array's Attributes](#NumPy-Array's-Attributes)</span>
    *   <span>[<span class="toc-item-num">2.2  </span>What advantages do NumPy arrays offer over (nested) Python lists?](#What-advantages-do-NumPy-arrays-offer-over-(nested)-Python-lists?)</span>
    *   <span>[<span class="toc-item-num">2.3  </span>Numpy Array (ndarry) can have multi-dimension](#Numpy-Array-(ndarry)-can-have-multi-dimension)</span>
*   <span>[<span class="toc-item-num">3  </span>Creating NumPy Arrays](#Creating-NumPy-Arrays)</span>
    *   <span>[<span class="toc-item-num">3.1  </span>Make “Empty” NumPy Array](#Make-“Empty”-NumPy-Array)</span>
    *   <span>[<span class="toc-item-num">3.2  </span>Load NumPy Arrays From Text](#Load-NumPy-Arrays-From-Text)</span>
*   <span>[<span class="toc-item-num">4  </span>Save NumPy Arrays](#Save-NumPy-Arrays)</span>
*   <span>[<span class="toc-item-num">5  </span>NumPy Broadcasting](#NumPy-Broadcasting)</span>
*   <span>[<span class="toc-item-num">6  </span>Array Mathematics](#Array-Mathematics)</span>
    *   <span>[<span class="toc-item-num">6.1  </span>Mathematics Operation](#Mathematics-Operation)</span>
    *   <span>[<span class="toc-item-num">6.2  </span>Logic Operation](#Logic-Operation)</span>
*   <span>[<span class="toc-item-num">7  </span>Manipulate NumPy Array](#Manipulate-NumPy-Array)</span>
    *   <span>[<span class="toc-item-num">7.1  </span>Subset, Slice, And Index Arrays](#Subset,-Slice,-And-Index-Arrays)</span>
        *   <span>[<span class="toc-item-num">7.1.1  </span>Indexing and Subseting NumPy Array](#Indexing-and-Subseting-NumPy-Array)</span>
        *   <span>[<span class="toc-item-num">7.1.2  </span>Slicing NumPy Array](#Slicing-NumPy-Array)</span>
    *   <span>[<span class="toc-item-num">7.2  </span>Common Two-Dimensional Slicing for Machine Learning](#Common-Two-Dimensional-Slicing-for-Machine-Learning)</span>
        *   <span>[<span class="toc-item-num">7.2.1  </span>Split Input and Output Features](#Split-Input-and-Output-Features)</span>
        *   <span>[<span class="toc-item-num">7.2.2  </span>Split Train and Test Rows](#Split-Train-and-Test-Rows)</span>
    *   <span>[<span class="toc-item-num">7.3  </span>Reshaping And Resizing Arrays](#Reshaping-And-Resizing-Arrays)</span>
        *   <span>[<span class="toc-item-num">7.3.1  </span>Reshape Array for Machine Learning](#Reshape-Array-for-Machine-Learning)</span>
            *   <span>[<span class="toc-item-num">7.3.1.1  </span>Reshape 1D to 2D Array](#Reshape-1D-to-2D-Array)</span>
            *   <span>[<span class="toc-item-num">7.3.1.2  </span>Reshape 2D to 3D Array](#Reshape-2D-to-3D-Array)</span>
            *   <span>[<span class="toc-item-num">7.3.1.3  </span>Transpose NumPy Arrays](#Transpose-NumPy-Arrays)</span>
        *   <span>[<span class="toc-item-num">7.3.2  </span>Additional Shape Method](#Additional-Shape-Method)</span>
            *   <span>[<span class="toc-item-num">7.3.2.1  </span>Append Arrays](#Append-Arrays)</span>
            *   <span>[<span class="toc-item-num">7.3.2.2  </span>Insert And Delete Array Elements](#Insert-And-Delete-Array-Elements)</span>
            *   <span>[<span class="toc-item-num">7.3.2.3  </span>Join And Split Arrays](#Join-And-Split-Arrays)</span>
            *   <span>[<span class="toc-item-num">7.3.2.4  </span>Sorting Arrays](#Sorting-Arrays)</span>
*   <span>[<span class="toc-item-num">8  </span>End of tutorial.](#You've-reached-the-end-of-this-tutorial.)</span>

## Contributing

Please feels free to contribute to this tutorial. If there are any mistake or typo, simply create an issue and i will fix it as soon as I can.

## Authors

* **Hoang Tung Lam** - [lamhoangtung](https://github.com/lamhoangtung)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
