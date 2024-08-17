<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vector Concepts in Linear Algebra</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML"></script>
</head>
<body>
    <h1>Vector Concepts in Linear Algebra</h1>
    <!-- Your content here -->
    <p>Let's break down the concepts of <strong>subspace</strong>, <strong>basis</strong>, <strong>dimension</strong>, and <strong>span</strong> using the vector:</p>
    <p>\[ \mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix} \]</p>
    <p>in the context of \( \mathbb{R}^2 \).</p>
    <h2>1. Subspace</h2>
    <p>A <strong>subspace</strong> refers to a set of vectors that is closed under vector addition and scalar multiplication and includes the zero vector. For a single vector in \( \mathbb{R}^2 \), the subspace it generates is a line through the origin in the direction of that vector.</p>
    <p>Subspace Generated by \( \mathbf{v} \): The subspace generated by the vector</p>
    <p>\[ \mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix} \]</p>
    <p>is all scalar multiples of this vector. This is a line in \( \mathbb{R}^2 \) passing through the origin and the point \( (3, 4) \).</p>
    <p>Mathematically, this subspace can be expressed as:</p>
    <p>\[ \text{span} \left\{ \begin{pmatrix} 3 \\ 4 \end{pmatrix} \right\} = \left\{ c \begin{pmatrix} 3 \\ 4 \end{pmatrix} \mid c \in \mathbb{R} \right\} \]</p>
    <h2>2. Basis</h2>
    <p>A <strong>basis</strong> for a subspace is a set of vectors that spans the subspace and is linearly independent. For a single vector \( \mathbf{v} \), the basis for the subspace it generates is simply</p>
    <p>\[ \left\{ \mathbf{v} \right\} \]</p>
    <p>Basis for the Subspace: The basis for the subspace generated by</p>
    <p>\[ \mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix} \]</p>
    <p>is:</p>
    <p>\[ \left\{ \begin{pmatrix} 3 \\ 4 \end{pmatrix} \right\} \]</p>
    <h2>3. Dimension</h2>
    <p>The <strong>dimension</strong> of a subspace is the number of vectors in its basis. For a line through the origin in \( \mathbb{R}^2 \) (which is the subspace generated by a single non-zero vector), the dimension is 1.</p>
    <p>Dimension: The dimension of the subspace generated by \( \mathbf{v} \) is 1, as it is spanned by a single vector.</p>
    <h2>4. Span</h2>
    <p>The <strong>span</strong> of a set of vectors is the set of all possible linear combinations of those vectors. For a single vector \( \mathbf{v} \), its span is the line in the vector space that includes all scalar multiples of that vector.</p>
    <p>Span of \( \mathbf{v} \): The span of</p>
    <p>\[ \mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix} \]</p>
    <p>is:</p>
    <p>\[ \text{span} \left\{ \begin{pmatrix} 3 \\ 4 \end{pmatrix} \right\} = \left\{ c \begin{pmatrix} 3 \\ 4 \end{pmatrix} \mid c \in \mathbb{R} \right\} \]</p>
    <p>This is a line through the origin in the direction of the vector</p>
    <p>\[ \begin{pmatrix} 3 \\ 4 \end{pmatrix} \]</p>
    <h2>Summary</h2>
    <ul>
        <li><strong>Subspace</strong>: The line through the origin in \( \mathbb{R}^2 \) along the direction of</li>
        <li>\[ \begin{pmatrix} 3 \\ 4 \end{pmatrix} \]</li>
        <li><strong>Basis</strong>: \[ \left\{ \begin{pmatrix} 3 \\ 4 \end{pmatrix} \right\} \]</li>
        <li><strong>Dimension</strong>: 1</li>
    </ul>
</body>
</html>
