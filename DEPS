# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '5f6c7176c5483da9af6432afb3dd962e4f8873a1',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'c3a5612cef04251d4a44e3f6bdf5a3adf9417548',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '9268f3057354a2cb65991ba5f38b16d81e803692',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5d01ec711f3077a89f33c7818d737cfa5dd932d6',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'df274657d83f3bd8c77aef816c1cbf27352a948b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '466498bc64eb77955c3b782f0127520548224de0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7f6326618226225269a274869ac638b870c8fe2b',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ea43e2f5e51e9ad958a40fdce981f2f0abf09cb5',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f17bbe1b05c8010a31ae677b6579f87f3de5716c',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
