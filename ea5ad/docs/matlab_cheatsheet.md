# Quick MATLAB Cheatsheet

```matlab
% Comment
x = 10;                       % Semicolon hides output
v = [1, 2, 3];                % Row vector
m = [1, 2; 3, 4];             % Matrix
v(1)                           % Indexing starts at 1
v(end)                         % Last element

data = readtable("file.csv");
data.X                         % Table column
data{:, {"X","Y","Z"}}         % Numeric array

if x > 5
    disp("Large");
else
    disp("Small");
end

for i = 1:10
    disp(i);
end

function result = square_number(x)
    result = x^2;
end

= assigns; == compares.
*, /, and ^ are matrix operations.
.*, ./, and .^ are element-wise operations.
&& and || operate on logical conditions.
height(table) returns the number of rows.
size(array) returns array dimensions.
addpath("src/geometry") makes functions available.
clear; clc; close all; resets the workspace.